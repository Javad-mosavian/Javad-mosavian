<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    ul {
        margin: 0;
        padding: 0;
        display: flex;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    ul li {
        list-style: none;
        margin: 0 15px;
    }

    ul li a {
        position: relative;
        display: block;
        width: 60px;
        height: 60px;
        text-align: center;
        line-height: 60px;
        background: #fff;
        border-radius: 50%;
        font-size: 30px;
        color: #666;
        transition: .5s;
    }

    ul li a:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 50%;
        background: #ffee10;
        transition: .5s;
        transform: scale(.9);
        z-index: -1;
    }

    ul li a:hover:before {
        transform: scale(1.1);
        box-shadow: 0 0 15px #ffee10;
    }

    ul li a:hover {
        color: #ffee10;
        box-shadow: 0 0 5px #ffee10;
        text-shadow: 0 0 5px #ffee10;
    }
</style>

<ul>
    <li><a href="#"><img style="width: 100%; height: 100%; scale: 0.6;" src="https://skillicons.dev/icons?i=html" /></a></li>
    <li><a href="#"><img style="width: 100%; height: 100%; scale: 0.6;" src="https://skillicons.dev/icons?i=css" /></a></li>
    <li><a href="#"><img style="width: 100%; height: 100%; scale: 0.6;" src="https://skillicons.dev/icons?i=tailwindcss" /></a></li>
    <li><a href="#"><img style="width: 100%; height: 100%; scale: 0.6;" src="https://skillicons.dev/icons?i=git" /></a></li>
</ul>
