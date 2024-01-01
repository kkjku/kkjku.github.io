<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Chúc Mừng Năm Mới 2024</title>
    <meta content="width=device-width,initial-scale=1,user-scalable=no" name="viewport">
    <meta content="yes" name="mobile-web-app-capable">
    <meta content="yes" name="apple-mobile-web-app-capable">
    <meta content="#000000" name="theme-color">
    <link href="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/firework-burst-icon-v2.png" rel="shortcut icon"
        type="image/png">
    <link href="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/firework-burst-icon-v2.png" rel="icon"
        type="image/png">
    <link href="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/firework-burst-icon-v2.png"
        rel="apple-touch-icon-precomposed">
    <meta content="#000000" name="msapplication-TileColor">
    <meta content="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/firework-burst-icon-v2.png"
        name="msapplication-TileImage">
    <link href="https://fonts.googleapis.com/css?family=Russo+One" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css" rel="stylesheet">
    <link href="./happy_new_year.css" rel="stylesheet">
</head>

<body>
    <div class="container">
        <div class="loading-init">
            <div class="loading-init__header"></div>
            <div class="loading-init__status"></div>
        </div>
        <div class="remove stage-container">
            <div class="canvas-container" hidden id="firework-container"><canvas id="trails-canvas"></canvas><canvas
                    id="main-canvas"></canvas></div>
            <div class="controls">
                <div class="btn pause-btn"><svg fill="white" height="24" width="24">
                        <use href="#icon-pause" xlink:href="#icon-pause"></use>
                    </svg></div>
                <div class="btn sound-btn"><svg fill="white" height="24" width="24">
                        <use href="#icon-sound-off" xlink:href="#icon-sound-off"></use>
                    </svg></div>
                <div class="btn settings-btn"><svg fill="white" height="24" width="24">
                        <use href="#icon-settings" xlink:href="#icon-settings"></use>
                    </svg></div>
            </div>
            <div class="hide menu">
                <div class="menu__inner-wrap">
                    <div class="btn btn--bright close-menu-btn"><svg fill="white" height="24" width="24">
                            <use href="#icon-close" xlink:href="#icon-close"></use>
                        </svg></div>
                    <div class="menu__header">Settings</div>
                    <div class="menu__subheader">For more info, click any label.</div>
                    <form>
                        <div class="form-option form-option--select"><label class="shell-type-label">Shell Type</label>
                            <select class="shell-type"></select></div>
                        <div class="form-option form-option--select"><label class="shell-size-label">Shell Size</label>
                            <select class="shell-size"></select></div>
                        <div class="form-option form-option--select"><label class="quality-ui-label">Quality</label>
                            <select class="quality-ui"></select></div>
                        <div class="form-option form-option--select"><label class="sky-lighting-label">Sky
                                Lighting</label> <select class="sky-lighting"></select></div>
                        <div class="form-option form-option--select"><label class="scaleFactor-label">Scale</label>
                            <select class="scaleFactor"></select></div>
                        <div class="form-option form-option--checkbox"><label class="auto-launch-label">Auto
                                Fire</label> <input class="auto-launch" type="checkbox"></div>
                        <div class="form-option form-option--checkbox form-option--finale-mode"><label
                                class="finale-mode-label">Finale Mode</label> <input class="finale-mode"
                                type="checkbox"></div>
                        <div class="form-option form-option--checkbox"><label class="hide-controls-label">Hide
                                Controls</label> <input class="hide-controls" type="checkbox"></div>
                        <div class="form-option form-option--checkbox form-option--fullscreen"><label
                                class="fullscreen-label">Fullscreen</label> <input class="fullscreen" type="checkbox">
                        </div>
                        <div class="form-option form-option--checkbox"><label class="long-exposure-label">Open
                                Shutter</label> <input class="long-exposure" type="checkbox"></div>
                    </form>
                    <div class="credits">Passionately built Sayn Achhava.</div>
                </div>
            </div>
        </div>
        <div class="help-modal">
            <div class="help-modal__overlay"></div>
            <div class="help-modal__dialog">
                <div class="help-modal__header"></div>
                <div class="help-modal__body"></div><button class="help-modal__close-btn" type="button">Close</button>
            </div>
        </div>
    </div>
    <div class="oclt">Khương đẹp trai</div>
    <div class="feliz">Chúc mừng năm mới</div>
    <div class="ano_novo"><span>202</span> <span class="seis">3</span> <span class="sete">4</span>
        <div class="balao"></div>
    </div>
    <div class="f1"><span><i></i></span> <span><i></i></span> <span><i></i></span></div>
    <div class="f2"><span><i></i></span> <span><i></i></span> <span><i></i></span></div>
    <div class="f3"><span><i></i></span> <span><i></i></span> <span><i></i></span></div>
    <div class="f4"><span><i></i></span> <span><i></i></span> <span><i></i></span></div>
    <script src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/fscreen%401.0.1.js"></script>
    <script src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/Stage%400.1.4.js"></script>
    <script src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/329180/MyMath.js"></script>
    <script src="./happy_new_year.js"></script>
</body>

</html>
