function login() {
    const user = document.getElementById("username").value;
    const pass = document.getElementById("password").value;

    if (user === "shipper" && pass === "123") {
        window.location.href = "dashboard.html";
    } else {
        document.getElementById("error").innerText = "Sai tài khoản hoặc mật khẩu!";
    }
}
