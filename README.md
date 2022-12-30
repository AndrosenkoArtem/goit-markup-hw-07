    /* основной цвет #212121 */
    /* второстепенный цвет #757575 */
    /* синий цвет #2196F3 */
    /* меил и номер телефона футер rgba(255, 255, 255, 0.6); */
    /* цвет фона команды #F5F4FA */
    :root {
        --primary-text-color: #212121;
        --title-text-color: #757575;
        --accent-color: #2196F3;
        --white-text: #F5F4FA;
        --black-color: #000000;
        --background-color: #ffffff;
        --dopp-color: #ddddff;
    }
    html {
        scroll-behavior: smooth;
    }
    body {
        color: var(--title-text-color);
        background-color: var(--background-color);
        font-family: Roboto, sans-serif;
        padding-top: 82.20px;
    }
    button {
        cursor: pointer;
        transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    img {
        display: block;
        max-width: 100%;
        height: auto;
    }
    a {
        transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .background-header {
        background-color: var(--background-color);
        position: fixed;
        width: 100%;  
        top: 0;
        z-index: 1;
    }
    .container {
        width: 1200px;
        margin-left: auto;
        margin-right: auto;
        padding-left: 15px;
        padding-right: 15px;
    }
    .header-container {
        display: flex;
        align-items: center;
        justify-content: center;
    }
    /* logo */
    .logo {
        color: var(--black-color);
        font-family: Raleway;
        font-size: 26px;
        line-height: 1.2;
        letter-spacing: 0.03em;
        text-decoration: none;
        padding-top: 24px;
        padding-bottom:25px;
    }
    .logo-blue {
        color: var(--accent-color)
    }
    ul {
        list-style: none;
        padding: 0;
        margin-top: 0;
        margin-bottom: 0;
    }
    .site-nav {
        display: flex;
        margin-left: 85px;
    }
    .site-nav li:not(:last-child) {
        margin-right: 50px;
    }
    .site-nav .link{
        color: var(--primary-text-color);
        text-decoration: none;
        font-weight: 500;
        font-size: 14px;
        line-height: 1.3;
        letter-spacing: 0.02em;
    }
    .site-nav .link.current {
        color: var(--accent-color);
    }
    .site-nav__line{
        position: relative;
    }
    .current::after {
        content: "";
        position: absolute;
        left: 0;
        height: 4px;
        width: 100%;
        background-color: #2196F3;
        bottom: 0;
        border-radius: 4px;
    }
    .site-nav .link:hover,
    .site-nav .link:focus {
        color: var(--accent-color);
    }
    .mail-icon {
        width: 16px;
        height: 11px;
        padding-right: 10px;
    }
    .mail {
        fill: var(--title-text-color);
        cursor: pointer;
        margin-right: 10px;
        transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);

    }
    .mail-list {
        display: flex;
        margin-left: auto;
    }
    .tel-icon {
        margin-left: 30px;
    }
    .telephone {
        margin-right: 10px;
        fill: var(--title-text-color);
    }
    .link_padding {
        display: block;
        padding: 32px 0px;
    }
    .mail-hover {
        display: flex;
        align-items: center;
        color: var(--title-text-color);
        text-decoration: none;
        font-weight: 500;
        font-size: 14px;
        line-height: 1.3;
        letter-spacing: 0.02em;
        
    }
    .mail-hover:hover,
    .mail-hover:focus{
        color: var(--accent-color);
    }

    .mail-hover:hover svg,
    .mail-hover:focus svg{
        fill: var(--accent-color);
    }
    .tel-hover {
        color: #757575;
        display: flex;
        align-items: center;
        text-decoration: none;
        font-weight: 500;
        font-size: 14px;
        line-height: 1.3;
        letter-spacing: 0.02em;
        
    }
    .tel-hover:hover,
    .tel-hover:focus {
        color: var(--accent-color);
    }
    .tel-hover:hover .telephone,
    .tel-hover:focus .telephone {
        fill: var(--accent-color);
        transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
        .hero {
        margin-left: auto;
        margin-right: auto;
    }
    .background-hero {
        text-align: center;
        padding-top: 200px;
        padding-bottom: 200px;
        min-width: 1200px;
        max-height: 100%;
        margin-left: auto;
        margin-right: auto;
        background-image: linear-gradient(0deg,
        rgba(47, 48, 58, 0.8),
        rgba(47, 48, 58, 0.8)
         ),
         url('../images/hero-background.jpg');
         background-repeat: no-repeat;
         background-position: center;
    }
        .hide-title {
        position: absolute;
        width: 1px;
        height: 1px;
        margin: -1px;
        border: 0px;
        padding: 0px;
        clip: rect(0 0 0 0);
        overflow: hidden;
    }
    .hero-title {
        color: var(--background-color);
        width: 696px;
        margin-top: 0;
        margin-bottom: 30px;
        font-weight: 900;
        font-size: 44px;
        line-height: 1.4;
        letter-spacing: 0.06em;
        text-transform: uppercase;
        margin-left: auto;
        margin-right: auto;
    }
    
    .feather-item__background {
        background-color: var(--white-text);
        width: 270px;
        height: 120px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .feather-list {
        display: flex;
        padding-top: 94px;
        padding-bottom: 94px;
        margin: 0;
        justify-content: center;
    }
    .feather-item {
        justify-content: center;
        width: 270px;
    }
    .feather-list .feather-item:not(:first-child) {
        margin-left: 30px;
    }
    .feather-item__title {
        color: var(--primary-text-color);
    }
    .feather-itemtitle {
        font-size: 14px;
        line-height: 1.3px;
        letter-spacing: 0.03em;
        text-transform: uppercase;
        margin-top: 30px;
    }
    .feather-item__subtitle {
        font-size: 14px;
        line-height: 1.7;
        letter-spacing: 0.03em;
        margin: 0;
        padding: 0;

    }
    .margin-text {
        padding-bottom: 94px;
    }
    .header {
        color: var(--primary-text-color);
        font-size: 36px;
        line-height: 1.2;
        text-align: center;
        letter-spacing: 0.03em;
        margin: 0;
        padding: 0;
        margin-bottom: 50px;
    }
    .activity {
        display: flex;
        justify-content: center;
    }

    .activity__title {
        color: var(--background-color);
        font-size: 14px;
        line-height: 1.2;
        letter-spacing: 0.03em;
        text-transform: uppercase;
        margin: 0;
        padding: 0;
    }
    .activity__backgroound {
        background: rgba(47, 48, 58, 0.8);
        position: absolute;
        bottom: 0;
        width: 370px;
        height: 70px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .text-position {
        position: relative;
    }
    .activity .activity__img:not(:first-child) {
        margin-left: 30px;
        position: relative;
    }
    .bcg-color {
        background-color: var(--white-text);
        padding-top: 94px;
        padding-bottom: 94px;
    }
    .team-name {
        display: flex;
        justify-content: center;
        position: relative;
    }
    .team-name .team-item:not(:first-child) {
        margin-left: 30px;
        box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2);
        border-radius: 0px 0px 4px 4px;
        
    }
    .team-background {
        box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2);
        border-radius: 0px 0px 4px 4px;
        
    }
    .team-title {
        text-align: center;
        background-color: var(--background-color);
    }
    .name-title {
        color: var(--primary-text-color);
        font-size: 16px;
        line-height: 1.2;
        letter-spacing: 0.03em;
        margin: 0;
        padding-top: 30px;
    }
    .name-subtitle {
        display: inline-block;
        font-weight: 400;
        font-size: 16px;
        line-height: 1.2px; 
        letter-spacing: 0.03em;

    }
    .social-list {
        display: flex;
        width: 206px;
        justify-content: space-between;
    }
    .team-flex {
        display: flex;
        justify-content:space-between;
        width: 206px;
        margin-left: auto;
        margin-right: auto;
        padding-bottom: 22px;
        padding-top: 16px;
    }
    .social-svg {
        width: 20px;
        height: 20px;
        transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .social-network  {
        display: flex;
        width: 44px;
        height: 44px;
        background-color: #fff;
        border-radius: 50px;
        align-items: center;
        justify-content: center;
        transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .social-network:hover {
        background-color: #2196F3;
    }
    .social-network:hover .social-svg  {
        fill: #ffff;
    }
    .social-svg {
        fill: #afb1b8;
    }
    .button
     {
        color: var(--background-color);
        margin-left: auto;
        margin-right: auto;
        padding: 10px 32px;
        min-width: 136px;
        text-align: center;
        background-color: var(--accent-color);
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
        border:1px solid var(--accent-color);
        border-radius: 4px;
        font-weight: 700;
        font-size: 16px;
        line-height: 1.9; 
        letter-spacing: 0.06em;

    }
    .button:hover,
    .button:focus {
        color: rgba(225, 225, 225, 0.7);

    }
    /* .hide-title {
        position: absolute;
        width: 1px;
        height: 1px;
        margin: -1px;
        border: 0px;
        padding: 0px;
        clip: rect(0 0 0 0);
        overflow: hidden;
    } */
    .social-svg-footer {
        width: 20px;
        height: 20px;
        fill: #fff;
    }
    .social-network-footer  {
        display: flex;
        width: 44px;
        height: 44px;
        background: #474858;
        border-radius: 50px;
        align-items: center;
        justify-content: center;
        transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .social-network-footer:hover {
        background-color: #2196F3;
    }
    .social-network:hover .social-svg  {
        fill: #ffff;
    }
    .margin-recrut {
        padding-top: 94px;
        padding-bottom: 94px;
    }
    .regular-icon {
        display: flex;
        justify-content: space-between;
    }
    .regular-div {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 170px;
        height: 90px;
        border: 1px solid #AFB1B8;
        border-radius: 4px;
        transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .regular-div:hover {
        border-color: #2196F3;
    }
    .regular-svg {
        fill: rgba(175, 177, 184, 1);
        transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .regular-div:hover .regular-svg {
        fill: var(--accent-color);
    }
    .regular-img a:hover {
        --color1: #2196F3;
    }
    .width-footer {
        width: 1170px;
        margin: auto;
    }
    .background-footer {
        background: #2F303A;
    }
    .footer-porfolio {
        width: 1200px;
        margin: auto;
    }
    .button-flex {
        display: flex;
        margin-top: 20px;
    }
    .lesia {
        text-decoration: none;
        color: var(--background-color);
    }
    .email-footer-button {
        color: rgba(255, 255, 255, 0.6);
        padding-left: 10px;
        background-color: rgba(47, 48, 58, 1);
        border: 1px solid rgba(255, 255, 255, 0.3);
        filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
        border-radius: 4px;
        font-size: 16px;
        line-height: 1.3;
        letter-spacing: 0.03em;
        width: 358px;
    }
    .button-subscribe {
        color: var(--background-color);
        background-color: var(--accent-color);
        align-items: center;
        border:1px solid var(--accent-color);
        display: flex;
        padding: 10px 28px 10px 29px;
        min-width: 109px;
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
        border-radius: 4px;
        font-weight: 700;
        font-size: 16px;
        line-height: 1.9;
        letter-spacing: 0.06em;
        margin-left: 12px;
    }
    .button-subscribe:hover,
    .button-subscribe:focus{
        color: rgba(225, 225, 225, 0.7);
    }
    .telegram-icon {
        margin-left: 10px;
        fill: #fff;
        transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .button-subscribe:hover svg,
    .button-subscribe:focus svg {
        fill: rgba(225, 225, 225, 0.7);
    }
    .mail-footer {
        display: block;
        color: rgba(250, 250, 250, 0.6);
        text-decoration: none;
        font-style: normal;
        font-size: 14px;
        line-height: 1.7;
        letter-spacing: 0.03em;
    }
    .mail-footer:hover,
    .mail-footer:focus {
        color: var(--accent-color);
    }
    .tel-footer {
        display: block;
        color: rgba(250, 250, 250, 0.6);
        text-decoration: none;
        font-style: normal;
        font-size: 14px;
        line-height: 1.7;
        letter-spacing: 0.03em;
        margin-top: 9px;
    }
    .tel-footer:hover,
    .tel-footer:focus {
        color: var(--accent-color);
    }
    .join-container > b {
        display: inline-block;
        margin-bottom: 20px;
    }
    .biography {
        color: var(--background-color);
        font-style: normal;
        font-weight: 400;
        font-size: 14px;
        line-height: 1.7;
        letter-spacing: 0.03em;
        margin: 0;
        padding: 0;
        margin-top: 20px;
        margin-bottom: 9px;
        width: 231px;
        
    }
    .join-and-subscribe {
        color: var(--background-color);
        font-size: 14px;
        line-height: 1.1;
        letter-spacing: 0.03em;
        text-transform: uppercase;
    }
    .footer-flex {
        display: flex;
        align-items: baseline;
        justify-content: space-between;
        background-color: #2F303A;
        width: 1170px;
        padding-top: 72px;
        padding-bottom: 100px;
    }
    .adress-footer .logo-footer {
        font-family: 'Raleway';
        color: var(--background-color);
        text-decoration: none;
        font-weight: 700;
        font-size: 26px;
        line-height: 1.2px;
        letter-spacing: 0.03em;
    }
    .logo-white {
        color: var(--accent-color);
    }
    .logo:hover {
        color: var(--accent-color)
    }
    .adress-footer .logo-footer:hover,
    .adress-footer .logo-footer:focus {
        color: var(--accent-color)
    }


    /* Portfolio css */
    .background-color {
        padding-top: 93px;
        width: 1170px;
    }
    .filter {
        display: flex;
        justify-content: center;
    }
    .filter li {
        margin-right: 8px;
    }
    .marketing {
        margin: 0;
    }
    .filter .filter-button {
        color: var(--primary-text-color);
        background-color: var(--white-text);
        border: none;
        border-radius: 4px;
        font-weight: 500;
        font-size: 16px;
        line-height: 26px;
        text-align: center;
        letter-spacing: 0.03em;
        display: inline-block;
        padding: 6px 22px;
        min-width: 73px;
        transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
        color 250ms cubic-bezier(0.4, 0, 0.2, 1),
        box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .filter .filter-button:hover,
    .filter .filter-button:focus {
        color: #ffff;
        background-color: var(--accent-color);
        box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px 1px 2px rgba(0, 0, 0, 0.08), 0px 2px 2px rgba(0, 0, 0, 0.12);
    }
    .market__photo {
        text-decoration: none;
    }
    .market-list:hover,
    .market-list:focus {
        box-shadow: 1px 4px 6px 0px #00000029, 0px 4px 4px 0px #0000000F, 0px 1px 1px 0px #0000001F;
    }
    .market__photo:hover .market__info, 
    .market__photo:focus .market__info { 
    transform: translateY(0);
    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .filter-padding {
        padding-top: 50px;
    }
    .market-list {
        margin-right: 30px;
        margin-bottom: 30px;
        width: calc((100% - 60px) / 3);
        transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);
    }
    .market__item {
        background-color: #FFFFFF;
        border-left: 1px solid #EEEEEE;
        border-right: 1px solid #EEEEEE;
        border-bottom: 1px solid #EEEEEE;
        padding: 20px 24px ;
    }
    .market-list:nth-child(3n) {
        margin-right: 0px;
    }
    .market-list:nth-last-child(-n + 3) {
        margin-bottom: 0;
      }
    .catalog {
        display: flex;
        flex-wrap: wrap;
        text-align:center;

        margin-left: auto;
        margin-right: auto;
        justify-content: center;
        padding-bottom: 94px;
    }
    .market__title {
        color: var(--primary-text-color);
        font-size: 18px;
        margin: 0;
        line-height: 2;
        letter-spacing: 0.06em;
        margin-bottom: 4px;
        display: flex
    } 
    .market__subtitle {
        color: var(--title-text-color);
        font-size: 16px;
        margin: 0;
        line-height: 1.9;
        letter-spacing: 0.03em;
        display: flex
    }
    .market__info {
        position: absolute;
        height: 100%;
        color: var(--background-color);
        background: rgba(33, 150, 243, 0.9);
        align-items: center;
        top: 0;
        left: 0;
        font-size: 18px;
        margin: auto;
        line-height: 28px;
        letter-spacing: 0.03em;
        display: flex;
        padding: 0px 24px;
        transform: translateY(101%);
    }
    .market__tehnoqack {
        position: relative;
        overflow: hidden;
    }
    .test-inline {
        display: flex;
        position: relative;
    }
    .backdrop {
        position: fixed;
        z-index: 1;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(000, 000, 000, 0.8);
        transition: opacity 100ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .backdrop.is-hidden{
        opacity: 0;
        pointer-events: none;
    }
    .backdrop.is-hidden .modal {
        transform: translate(-50%, -50%) scale(1.1);
    }
    .modal {
        position: relative;
        min-width: 528px;
        min-height: 581px;
        background-color: #Ffffff;

        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) scale(0.9);
        transition: transform 1000ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .close-modal {
        z-index: 1;
        position: absolute;
        width: 30px;
        height: 30px;
        top: 8px;
        right: 8px;
        border-radius: 50px;
        border: 1px solid rgba(0, 0, 0, 0.1);
        background-color: #ffffff;
    }
    .cross-icon {
        width: 11px;
        height: 11px;
        transition: fill 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .close-modal:hover .cross-icon,
    .close-modal:focus .cross-icon {
        fill: #2196F3;
    }
    .color-slogan {
    color: #212121;
    margin-top: 40px;
    margin-bottom: 30px;
    }
    .input-elements input {
        height: 40px;
        border: 1px solid #757575;
        border-radius: 4px;
        padding-left: 42px;
        outline: none;
    }
    .input-elements {
        position: relative;
        display: flex;
        flex-direction: column;
        width: 448px;
        margin-left: auto;
        margin-right: auto;
        margin-bottom: 28px;
        transition: transform 250ms cubic-bezier(0.075, 0.82, 0.165, 1),
        color 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .input-elements input:focus,
    .input-elements textarea:focus,
    .input-elements input:not(:placeholder-shown),
    .input-elements textarea:not(:placeholder-shown){
        border: 1px solid var(--accent-color);
    }
    .input-elements:focus-within .position-lable,
    .input-elements input:not(:placeholder-shown) + .position-lable {
        color: var(--accent-color);
        transform: translateY(-28px) translateX(-30px) scale(0.8);
    }
    .input-elements:focus-within .position-textarea,
    .input-elements textarea:not(:placeholder-shown) + .position-textarea {
        color: var(--accent-color);
        transform: translateY(-30px) translateX(-5px) scale(0.8);
    } 
    .input-elements:focus-within .position-tel,
    .input-elements input:not(:placeholder-shown) + .position-tel {
        color: var(--accent-color);
        transform: translateY(-30px) translateX(-34px) scale(0.8);
    }
    .input-elements:focus-within .icon-form,
    .input-elements input:not(:placeholder-shown) ~ .icon-form {
        fill: var(--accent-color);
    }
    .position-lable {
    position: absolute;
    bottom: 12px;
    left: 44px;
    transition: transform 250ms cubic-bezier(0.075, 0.82, 0.165, 1),
    color 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }

    .icon-form {
        position: absolute;
        bottom: 15px;
        left: 18px;
        transition: fill 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .mail-form {
        width: 17px;
        height: 13px;
    }
    .tel-form {
        width: 14px;
        height: 14px;
    }
    .contact-form {
        width: 13px;
        height: 13px;
    }
    textarea {
        padding: 12px 16px;
        outline: none;
        resize: none;
        height: 120px;
        border: 1px solid #757575;
        border-radius: 4px;
    }
    .position-textarea {
        position: absolute;
        top: 12px;
        left: 16px;
        transition: transform 250ms cubic-bezier(0.075, 0.82, 0.165, 1),
        color 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .checkbox-css {
        width: 400px;
        margin-left: auto;
        margin-right: 51px;
        margin-bottom: 30px;
    }
    .checkbox {
        position: absolute;
            width: 1px;
            height: 1px;
            margin: -1px;
            border: 0px;
            padding: 0px;
            clip: rect(0 0 0 0);
            overflow: hidden;
    }
    .cursor-pointer {
        cursor: pointer;
    }
    .position-checkbox {
        margin-right: 51px;
    }
    .checked-off {
        position: absolute;
        left: 54px;
        display: inline-block;
        width: 18px;
        height: 17px;
        border: 1px solid #212121;
        border-radius: 2px;
        transition: background-image 250ms cubic-bezier(0.075, 0.82, 0.165, 1),
        background-color 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .checkbox:checked + .checked-off{
        background-image: url(../images/icon-check.svg);
        background-color: var(--accent-color);
        border: none;
        width: 18px;
        height: 17px;
        background-size: contain;
        background-origin: border-box;
    }
    .demom-contrant {
        color: var(--accent-color);
    }
    .btn-send {
        display: flex;
        margin-left: auto;
        margin-right: auto;
        padding: 10px 55px;
        background-color: var(--accent-color);
        color: var(--background-color);
        border: none;
        border-radius: 4px;
        transition: box-shadow 250ms cubic-bezier(0.075, 0.82, 0.165, 1),
        color 250ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }
    .btn-send:hover,
    .btn-send:focus {
        color: rgba(255, 255, 255, 0.7);
        box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.15);
    }