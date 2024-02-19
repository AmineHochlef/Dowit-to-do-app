<div class="authContainer">
    <form action="">
        <h1>Login</h1>
        <label for="">
            <input type="email" placeholder="Email">
        </label>
        <label for="">
            <input type="password" placeholder="Password">
        </label>
        <label for="">
            <input type="password" placeholder="Confirm Password">
        </label>
        <button type="button">Submit</button>
    </form>

</div>

<style>
    .authContainer {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        flex: 1;
        padding: 24px;
    }

    form {
        display: flex;
        flex-direction: column;
        gap: 14px;
        width: 400px;
        max-width: 100%;
        margin: 0 auto;
    }

    form input {
        width : 100%;
    }

    h1 {
        text-align: center;
    }

    form input {
        border: none;
        background: transparent;
        color: white;
        padding: 8px 14px;
    }

    form label {
        position: relative;
        border: 1px solid navy;
        border-radius: 5px;
    }

    form input:focus {
        border: none;
        outline: none; 
    }

    form button {
        background: navy;
        color: white;
        border: none;
        padding: 10px 0;
        border-radius: 5px;
        cursor: pointer;
    }

    form button:hover {
        background: blue;
    }
</style>