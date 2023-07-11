
<div class="navbar">

    <img src="/images/GMW.png" alt="gmw">
    <div class="routes">
        <a href="/">Home</a>
        <a href="/pages/about">About</a>
        <a href="https://shop.trusted-studios.eu">Shop</a>
    </div>
</div>

<style>
    .navbar {
        display: grid;
        grid-template-columns: repeat(3, 1fr);

        margin-top: 20px;
        margin-bottom: 20px;

        justify-items: center;
        align-items: center;
    }

    .routes {
        display: grid;
        grid-template-columns: repeat(3, 1fr);

        gap: 50%;
        
        justify-items: center;
        align-items: center;

        margin-right: 30%;
    }

    img {
        margin-left: 50px;

        background-repeat: no-repeat;
        object-fit: contain;

        width: 56px;
        height: 56px;

        justify-self: start;
    }

    a {
        font-family: var(--font-inter);
        font-weight: bold;

        color: white;
        text-decoration: none;
    }

    a:hover {
        background: linear-gradient(130.69deg, #8280ec 32.29%, #85ba88 49.33%, #fff);
        background-clip: text;
        -webkit-text-fill-color: transparent;

        transition: ease 0.3s;
    }
</style>