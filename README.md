# calorie-calculator 

HTML construction for your site 

example my code: 
```
<div class="calculating">
        <div class="container">
            <h2 class="title">Рассчитаем вашу потребность в калориях?
            </h2>
            <div class="calculating__field">
                <div class="calculating__subtitle">
                    Ваш пол
                </div>
                <div class="calculating__choose" id="gender">
                    <div id="famele"  class="calculating__choose-item calculating__choose-item_active">Женщина</div>
                    <div id="male" class="calculating__choose-item">Мужчина</div>
                </div>

                <div class="calculating__subtitle">
                    Ваша конституция
                </div>
                <div class="calculating__choose calculating__choose_medium">
                    <input type="text" id="height" placeholder="Введите рост" class="calculating__choose-item">
                    <input type="text" id="weight" placeholder="Введите вес" class="calculating__choose-item">
                    <input type="text" id="age" placeholder="Введите возраст" class="calculating__choose-item">
                </div>

                <div class="calculating__subtitle">
                    Выберите вашу физическая активность
                </div>
                <div class="calculating__choose calculating__choose_big">
                    <div data-ratio="1.2" id="low" class="calculating__choose-item">Низкая активность </div>
                    <div data-ratio="1.375" id="small" class="calculating__choose-item calculating__choose-item_active">Невысокая
                        активность</div>
                    <div data-ratio="1.55" id="medium" class="calculating__choose-item">Умеренная активность</div>
                    <div data-ratio="1.725" id="high" class="calculating__choose-item">Высокая активность</div>
                </div>

                <div class="calculating__divider"></div>

                <div class="calculating__total">
                    <div class="calculating__subtitle">
                        Ваша суточная норма калорий:
                    </div>
                    <div class="calculating__result">
                        <span>2700</span> ккал
                    </div>
                </div>
            </div>
        </div>
    </div>
```
