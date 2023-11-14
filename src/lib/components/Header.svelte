<header>
    <div class="comp">
        <a href="/" class="comp-name">
            <h2><span>BUSSIN</span></h2>
        </a>
    </div>

    <ul class="navlist">
        <li><a href="/">HOME</a></li>
        <li><a href="/">TERMINAL FACILITIES</a></li>
        <li><a href="/">LOST AND FOUND</a></li>
    </ul>

    <div class="social-icons">
        <p>f</p>
        <a href="https://twitter.com" class="social-icon"><img src="/path/to/twitter-icon.png" alt="Twitter">f</a>
    </div>
</header>

<style>
    header {
        position: fixed;
        width: 100%;
        top: 0;
        left: 0;
        z-index: 1000;
        display: flex;
        align-items: center;
        background: transparent;
        padding: 20px 5%;
        border-bottom: 1px solid transparent;
        transition: all 0.45s ease;
    }

    .comp-name {
        font-weight: 700;
        top: -30px;
        padding-left: 9px;
        margin-right: 25px;
        margin-left: -50px;
        text-decoration: none; 
    }

    .comp {
        display: flex;
        align-items: center;
    }

    .navlist {
        display: flex;
        list-style: none;
        padding: 0;
    }

    .navlist li {
        margin-right: 25px;
    }

    .navlist a {
        font-weight: 600;
        transition: all 0.45s ease;
        color: #0D0111;
        font-family: Poppins;
        font-size: 15.5px;
        font-style: normal;
        line-height: normal;
        text-decoration: none; 
    }

    .navlist a:hover {
        color: rgb(43, 198, 107);
    }

    .social-icons {
        display: flex;
        margin-left: auto; /* Move social icons to the right */
    }

    .social-icon {
        margin-left: 15px;
        display: flex;
        align-items: center;
        text-decoration: none;
    }

    .social-icon img {
        width: 20px; /* Adjust the width of the social icons */
        height: 20px; /* Adjust the height of the social icons */
    }
</style>
