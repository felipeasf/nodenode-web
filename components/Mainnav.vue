<template>
    <nav id="Mainnav">

        <NuxtLink to="/">
            <svg class="logo" width="62" height="28" viewBox="0 0 62 38" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M58.8522 0C59.7848 0 60.5426 0.289334 61.1255 0.868001C61.7084 1.44667 61.9999 2.17 61.9999 3.038V34.6657C61.9999 35.6061 61.6501 36.4017 60.9507 37.0527C60.29 37.6676 59.4545 37.975 58.4442 37.975C57.9001 37.975 57.3561 37.9027 56.812 37.758C56.3068 37.5772 55.9377 37.3421 55.7045 37.0527L34.3119 11.7722V34.937C34.3119 35.805 34.001 36.5283 33.3792 37.107C32.7963 37.6857 32.0191 37.975 31.0476 37.975C30.1149 37.975 29.3572 37.6857 28.7743 37.107C28.1914 36.5283 27.8999 35.805 27.8999 34.937V3.30925C27.8999 2.36892 28.156 1.4599 28.8167 0.845066C29.5161 0.194066 30.3096 0 31.0702 0C32.2063 0 32.8668 0.29945 33.7744 1.04225C34.682 1.78505 55.6462 26.3655 55.6462 26.3655V3.038C55.6462 2.17 55.9377 1.44667 56.5206 0.868001C57.1423 0.289334 57.9195 0 58.8522 0Z" fill="black" fill-opacity="0.25"/>
                <path d="M31.1411 0C32.0794 0 32.8418 0.289401 33.4283 0.868203C34.0147 1.447 34.3079 2.1705 34.3079 3.0387V34.6738C34.3079 35.6143 33.9561 36.4102 33.2523 37.0613C32.5877 37.6763 31.7471 37.9838 30.7305 37.9838C30.1832 37.9838 29.6358 37.9114 29.0884 37.7667C28.5802 37.5859 28.2088 37.3507 27.9742 37.0613L6.45107 11.775V34.9451C6.45107 35.8133 6.13829 36.5368 5.51273 37.1156C4.92627 37.6944 4.14432 37.9838 3.16689 37.9838C2.22855 37.9838 1.46615 37.6944 0.879691 37.1156C0.29323 36.5368 0 35.8133 0 34.9451V3.31001C0 2.36947 0.332328 1.5917 0.996983 0.976726C1.70074 0.325575 2.56088 0 3.57741 0C4.16387 0 4.73078 0.108526 5.27814 0.325578C5.86461 0.542627 6.29468 0.832027 6.56836 1.19378L27.9155 26.3716V3.0387C27.9155 2.1705 28.2087 1.447 28.7952 0.868203C29.4208 0.289401 30.2027 0 31.1411 0Z" fill="black" fill-opacity="1"/>
            </svg>
        </NuxtLink>
        <section class="sub-nav"> 
            <section class="button-group">
                <span>api.nodenode.org:5357</span>
                <a class="header-link" href="mailto:rami@nodenode.org">
                    Open a discussion
                </a>
                <a class="button" href="https://calendly.com/nodenode">
                    Schedule Now
                </a>
            </section>
        </section>
    </nav>
</template>

<style lang="scss">

    #Mainnav {
        flex-shrink: 0;
        flex-direction: row;
        display: flex;
        justify-content: space-between;
        position: fixed;
        width:100%;
        -webkit-backdrop-filter: blur(10px);
        backdrop-filter: blur(10px);

        .logo {
            background: rgba(255,255,255,0);
            padding:26px 20px;
            filter: invert(100%);
        }

        .header-link {
            border-bottom: 1px solid rgba(255,255,255,0.25);
            margin-right:20px;
            font-size:75%;

            &:hover {
                border-bottom: 1px solid rgba(255,255,255,1);
            }
        }

        span {
            font-size:75%;
            margin-right:20px;

            @media only screen and (max-width: 800px) {
                display:none;
            } 
        }
    }

</style>
