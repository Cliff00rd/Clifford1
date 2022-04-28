# Clifford1
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="styles.css" />
        <title>Login</title>
    </head>
    <body>
        <div class="bg" aria-hidden="true">
            <div class="bg__dot"></div>
            <div class="bg__dot"></div>
        </div>
        <form class="form" autocomplete="off">
            <div class="form__icon" aria-hidden="true"></div>
            <div class="form__input-container">
                <input
                    aria-label="User"
                    class="form__input"
                    type="text"
                    id="user"
                    placeholder=" "
                />
                <label class="form__input-label" for="user">Login</label>
            </div>
            <div class="form__input-container">
                <input
                    aria-label="Password"
                    class="form__input"
                    type="password"
                    id="password"
                    placeholder=" "
                />
                <label class="form__input-label" for="password">Hasło</label>
            </div>
            <div class="form__spacer" aria-hidden="true"></div>
            <button class="form__button">Zaloguj</button>
        </form>
    </body>
</html>
