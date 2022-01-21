# HTML-CSS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./assets/fonts/fontawesome-free-5.15.4-web/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
        integrity="sha512-NhSC1YmyruXifcj/KFRWoC561YpHpc5Jtzgvbuzx5VozKpWvQ+4nXhPdFgmx8xqexRcpAglTj9sIBWINXa8x5w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="./assets/css/base.css">
    <link rel="stylesheet" href="./assets/css/main.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
</head>

<body>
    <!-- block, element modifier: sự thay đổi cho element hoặc block -->
    <div class="app">
        <header class="header">
            <div class="grid">
                <nav class="header__navbar">
                    <ul class="header__navbar-list">
                        <!-- separate: gạch phân cách -->
                        <li class="header__navbar-item header__navbar-item--has-qr header__navbar-item--separate">
                            vào cửa hàng trên ứng dụng shoppe
                            <!-- header qr code -->
                            <div class="header__qr">
                                <img src="./assets/img/qr_code.png" alt="QR code" class="header__qr-img">
                                <div class="header__qr-apps">
                                    <a href="" class="header__qr-link">
                                        <img src="./assets/img/google_play.png" alt="Google play"
                                            class="header__qr-download-img">
                                    </a>
                                    <a href="" class="header__qr-link">
                                        <img src="./assets/img/app_store.png" alt="App Store"
                                            class="header__qr-download-img">
                                    </a>
                                </div>
                            </div>
                        </li>
                        <li class="header__navbar-item">
                            <span class="header__navbar-title--no-pointer">Kết nối</span>
                            <a href="https://www.facebook.com/chikkippo/" class="header__navbar-icon-link">
                                <i class="header__navbar-icon fab fa-facebook"></i>
                            </a>

                            <a href="" class="header__navbar-icon-link">
                                <i class="header__navbar-icon fab fa-instagram"></i>
                            </a>

                        </li>
                    </ul>

                    <ul class="header__navbar-list">
                        <li class="header__navbar-item header__navbar-item--has-notify">
                            <a href="" class="header__navbar-item-link">
                                <i class="header__navbar-icon fas fa-bell"></i>
                                Thông báo
                            </a>
                            <div class="header__notify">
                                <header class="header__notify-header">
                                    <h3>Thông báo mới nhận</h3>
                                </header>
                                <ul class="header__notify-list">
                                    <li class="header__notify-item header__notify-item--viewed">
                                        <a href="" class="header__notify-link">
                                            <span>
                                                <img src="https://beautyprincess.vn/wp-content/uploads/2019/04/nearanddear1-1508137616924.jpg"
                                                    alt="" class="header__notify-img">
                                            </span>
                                            <div class="header__notify-info">
                                                <span class="header__notify-name">[Tổng Hợp] 10+ Dòng Son Môi 3CE Chính
                                                    Hãng, Màu Cực Đẹp</span>
                                                <span class="header__notify-descriotion">Dòng son kem 3CE Liquid Lip
                                                    Color của thương hiệu 3CE luôn tốt.</span>
                                            </div>
                                        </a>
                                    </li>

                                    <li class="header__notify-item header__notify-item--viewed">
                                        <a href="" class="header__notify-link">
                                            <span>
                                                <img src="https://img.websosanh.vn/v10/users/review/images/en9vjkn4rtgag/son-moi-3ce-chinh-hang-1.jpg?compress=85"
                                                    alt="" class="header__notify-img">
                                            </span>
                                            <div class="header__notify-info">
                                                <span class="header__notify-name">Mỹ Phẩm 3Ce chính hãng</span>
                                                <span class="header__notify-descriotion">Mô tả mỹ Phẩm 3Ce chính
                                                    hãng</span>

                                            </div>
                                        </a>
                                    </li>

                                    <li class="header__notify-item">
                                        <a href="" class="header__notify-link">
                                            <span>
                                                <img src="https://congaiphaixinh.com/wp-content/uploads/2020/04/Son-3CE-Cloud-Lip-Tint.jpg"
                                                    alt="" class="header__notify-img">
                                            </span>
                                            <div class="header__notify-info">
                                                <span class="header__notify-name">Mỹ Phẩm 3Ce chính hãng</span>
                                                <span class="header__notify-descriotion">Mô tả mỹ Phẩm 3Ce chính
                                                    hãng</span>

                                            </div>
                                        </a>
                                    </li>
                                </ul>
                                <footer class="header__notify-footer">
                                    <a href="" class="header__notify-footer-btn">xem tất cả</a>
                                </footer>
                            </div>
                        </li>
                        <li class="header__navbar-item">
                            <a href="" class="header__navbar-item-link">
                                <i class="header__navbar-icon far fa-question-circle"></i>
                                Trợ giúp
                            </a>
                        </li>
                        <li class="header__navbar-item header__navbar-item--strong header__navbar-item--separate">Đăng
                            ký</li>
                        <!-- strong:chữ in đậm -->
                        <li class="header__navbar-item header__navbar-item--strong">Đăng nhập</li>
                    </ul>
                </nav>
            </div>
            <!-- chứa navbar -->
        </header>

        <div class="container">

        </div>

        <footer class="footer">

        </footer>
    </div>
    <!-- modal layout -->
    <div class="modal">
        <div class="modal__overlay"></div>

        <div class="modal__body">
            <!-- trọng tâm của body -->
            <!-- <div class="modal__inner"> content -->

            <!-- Register form -->
            <!-- <div class="auth-form">
                <div class="auth-form__container">
                    <div class="auth-form__header">
                        <h3 class="auth-form__heading">Đăng ký</h3>
                        <span class="auth-form__switch-btn">Đăng nhập</span>
                    </div>

                    <div class="auth-form__form">
                        <div class="auth-form__group">
                            <input type="text" class="auth-form__input" placeholder="Email của bạn">
                        </div>
                        <div class="auth-form__group">
                            <input type="password" class="auth-form__input" placeholder="Mật khẩu của bạn">
                        </div>
                        <div class="auth-form__group">
                            <input type="password" class="auth-form__input" placeholder="Nhập lại mật khẩu">
                        </div>
                    </div>

                    <div class="auth-form__aside">
                        <p class="auth-form__policy-text">
                            Bằng việc đăng ký, bạn đã đồng ý với shoppe về
                            <a href="" class="auth-form__text-link">Điều khoản dịch vụ</a>
                            <a href="" class="auth-form__text-link">Chính sách bảo mật</a>
                        </p>
                    </div>

                    <div class="auth-form__controls">
                        <button class="btn btn--normal auth-form__controls-back">TRỞ LẠI</button>
                        <button class="btn btn--primary">ĐĂNG KÝ</button>
                    </div>
                </div>

                <div class="auth-form__socials">
                    <a href="" class="auth-form__socials--facebook btn btn--size-s btn--with-icon">
                        <i class="auth-form__socials-icon fab fa-facebook-square"></i>
                        <span class="auth-form__socials-title">
                            Kết nối với Facebook
                        </span>
                    </a>
                    <a href="" class="auth-form__socials--google btn btn--size-s btn--with-icon">
                        <i class="auth-form__socials-icon fab fa-google"></i>
                        <span class="auth-form__socials-title">
                            Kết nối với Google
                        </span>
                    </a>
                </div>
            </div> -->


            <!-- Login form -->
            <div class="auth-form">
                <div class="auth-form__container">
                    <div class="auth-form__header">
                        <h3 class="auth-form__heading">Đăng nhập</h3>
                        <span class="auth-form__switch-btn">Đăng ký</span>
                    </div>

                    <div class="auth-form__form">
                        <div class="auth-form__group">
                            <input type="text" class="auth-form__input" placeholder="Email của bạn">
                        </div>
                        <div class="auth-form__group">
                            <input type="password" class="auth-form__input" placeholder="Mật khẩu của bạn">
                        </div>
                    </div>

                    <div class="auth-form__aside">
                        <div class="auth-form__help">
                            <a href="" class="auth-form__help-link auth-form__help-forgot">Quên mật khẩu</a>
                            <span class="auth-form__help-separate"></span>
                            <a href="" class="auth-form__help-link">Cần trợ giúp?</a>
                        </div>
                    </div>

                    <div class="auth-form__controls">
                        <button class="btn btn--normal auth-form__controls-back">TRỞ LẠI</button>
                        <button class="btn btn--primary">ĐĂNG NHẬP</button>
                    </div>
                </div>

                <div class="auth-form__socials">
                    <a href="" class="auth-form__socials--facebook btn btn--size-s btn--with-icon">
                        <i class="auth-form__socials-icon fab fa-facebook-square"></i>
                        <span class="auth-form__socials-title">
                            Kết nối với Facebook
                        </span>
                    </a>
                    <a href="" class="auth-form__socials--google btn btn--size-s btn--with-icon">
                        <i class="auth-form__socials-icon fab fa-google"></i>
                        <span class="auth-form__socials-title">
                            Kết nối với Google
                        </span>
                    </a>
                </div>
            </div>


            
        </div>
    </div>
</body>

</html>
