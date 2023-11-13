<header>
    <div class="comp">
        <a href="/" class="comp-name">
            <h2 style="margin-left: -5.8rem;"><span>BUSSIN</span></h2>
        </a>
    </div>

    <ul class="navlist">
        <li><a href="/">HOME</a></li>
        <li><a href="/">TERMINAL FACILITIES</a></li>
        <li><a href="/">LOST AND FOUND</a></li>
    </ul>
</header>

<style>
    header{
        position: fixed;
        width: 100%;
        top: 0;
        right: 0;
        z-index: 1000;
        display: flex;
        align-items: center;
        justify-content: space-between;
        background: transparent;
        padding: 20px 15%;
        border-bottom: 1px solid transparent;
        transition: all 0.45s ease;
        padding-left: 8.5%;
        padding-right: 8.5%;
        font-weight: 600;
    }

    .comp-name{
        font-weight: 700;
        top: -30px;
        padding-left: 9px;
    }

    .comp{
        display: flex;
        justify-items: center;
    }

    .navlist{
        display: flex;
        margin-left: -15rem;
    }

    .navlist a{
        color: var(--v-dark-purple);
        font-size: var(--small-font);
        font-weight:  600;
        margin: 0 25px;
        transition: all 0.45s ease;

        color: #0D0111;
        font-family: Poppins;
        font-size: 15.5px;
        font-style: normal;
        font-weight: 600;
        line-height: normal;
    }

    .navlist a:hover{
        color: rgb(43, 198, 107);
    }
</style>