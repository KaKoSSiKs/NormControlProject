<script>
    import {base} from "$app/paths";
    function sendEmail()
    {
        window.open('mailto:normcontrol@bk.ru?subject=Проверка документа на соответствие ГОСТ&body=Прикрепите файл к письму');
    }
</script>


<div class="_wrapper">
    <div class="_container">
        <div class="head-block">

        </div>
    </div>
</div>
<div class="_wrapper">
    <div class="_container">
        <div class="body">

            <div class="list-card">
                <div class="card" style="background-color: #d7e292">
                    <div class="card-image">
                        <img src="{base}/p1.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>Сверьте свою научную работу согласно нормам ГОСТ: быстро, надежно, эффективно</h3>
                    </div>
                </div>

                <div class="card" style="background-color: #f7de9e">
                    <div class="card-image">
                        <img src="{base}/p2.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>Освободите время для других нужд!</h3>
                    </div>
                </div>

                <div class="card" style="background-color: #f6a29b">
                    <div class="card-image">
                        <img src="{base}/p3.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>Больше не нужно копаться в нормативных документах</h3>
                    </div>
                </div>
            </div>
            <div class="input">
                <h2>Оставьте свою заявку на проверку вашего документа, написав нам на почту:</h2>
                <!--@ts-ignore-->
                <button class="button-19" on:click={() => sendEmail()}>
                    Оставить заявку
                </button>
            </div>
        </div>
    </div>
</div>
<div class="_wrapper">
    <div class="_container">
        <div class="instruction-block">
            <div class="image">
                <img src="{base}/reg.svg" alt="" width="300px"/>
            </div>
            <div class="grid-card">
                <div class="card" style="background-color: #8dddc0">
                    <div class="card-image">
                        <img src="{base}/1.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>Нажми на кнопку "Оставить заявку"</h3>
                    </div>
                </div>
                <div class="card" style="background-color: #86A5D9">
                    <div class="card-image">
                        <img src="{base}/2.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>Прикрепи к письму документ для проверки</h3>
                    </div>
                </div>
                <div class="card" style="background-color: #5F4BB6">
                    <div class="card-image">
                        <img src="{base}/3.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>Отправь и ожидай результат!</h3>
                    </div>
                </div>
                <div class="card" style="background-color: #e7508b">
                    <div class="card-image">
                        <img src="{base}/4.png" alt=""/>
                    </div>
                    <div class="card-title">
                        <h3>PROFFIT!!!</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
    .body {
        display: flex;
        gap: 50px;
        padding: 15px;
        border-top: 3px solid #000;
        border-bottom: 3px solid #000;
    }
    .list-card {
        display: flex;
        gap: 15px;
        flex-direction: column;

    }
    .card {
        box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px;
        display: flex;
        background-color: rgba(247, 214, 204, 0.5);
        padding: 25px;
        align-items: center;
        gap: 15px;
        border-radius: 20px;
        color: #141414;
    }
    .input {
        padding: 10px;
        display: flex;
        border-radius: 15px;
        justify-content: space-around;
        flex-direction: column;
    }
    .card-image img {
        width: 64px;
    }
    .button-19 {
        background-color: #1899D6;
        border: solid transparent;
        border-radius: 16px;
        border-width: 0 0 4px;
        box-sizing: border-box;
        color: #FFFFFF;
        cursor: pointer;
        display: inline-block;
        font-family: din-round,sans-serif;
        font-size: 15px;
        font-weight: 700;
        letter-spacing: .8px;
        line-height: 20px;
        margin: 0;
        outline: none;
        overflow: visible;
        padding: 13px 16px;
        text-align: center;
        text-transform: uppercase;
        touch-action: manipulation;
        transform: translateZ(0);
        transition: filter .2s;
        user-select: none;
        -webkit-user-select: none;
        vertical-align: middle;
        white-space: nowrap;
        width: 100%;
    }

    .button-19:after {
        background-clip: padding-box;
        background-color: #1CB0F6;
        border: solid transparent;
        border-radius: 16px;
        border-width: 0 0 4px;
        bottom: -4px;
        content: "";
        left: 0;
        position: absolute;
        right: 0;
        top: 0;
        z-index: -1;
    }

    .button-19:hover:not(:disabled) {
        filter: brightness(1.1);
        -webkit-filter: brightness(1.1);
    }

    .button-19:disabled {
        cursor: auto;
    }

    .button-19:active {
        border-width: 4px 0 0;
        background: none;
    }

    .grid-card {
        display: grid;
        grid-template-rows:repeat(4, 1fr);
        gap: 20px;
    }
    .instruction-block {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
</style>