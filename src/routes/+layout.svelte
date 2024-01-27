<script>
    import {base} from "$app/paths";
    import '/src/app.css'

</script>


<header>
    <div class="_container">
        <div class="header">
            <div class="logo">
                <img src="{base}/LogoProject.png" alt="logo" width="550px"/>
            </div>
            <div class="header-text">
                <h2>Автоматическое форматирование
                    научно-исследовательских работ</h2>
            </div>

        </div>
    </div>
</header>


<slot/>

<style>
    header {
        width: 100%;
        z-index: 100;
        padding: 5px 25px 5px 25px;
        @media (max-width: 767px) {
            max-width: none;
        }

    }
    .header {
        display: flex;
        justify-content: space-between;
        gap: 50px;
        text-align: right;

    }
    .header-text {
        display: flex;
        align-items: center;
    }
</style>