<template>
  <title>Account Login - Leetcode</title>
  <div class="box">
    <form>
      <img src="https://assets.leetcode.com/static_assets/public/webpack_bundles/images/logo.c36eaf5e6.svg"
           alt="LeetCode">
      <label>
        <input type="text" name="username" id="username" placeholder="Username or E-mail"/>
      </label>
      <label>
        <input type="password" name="password" id="password" placeholder="Password"/>
      </label>
      <button onclick="" type="submit">       Sign In         </button>
      <div class="actions">
        <a href="/accounts/password/reset/">Forgot Password?</a>
        <span
            data-cy="sign-up-link">Sign Up
            </span>
      </div>
      <p class="tips">or you can sign in with</p>
      <div><a href="https://leetcode.com/accounts/google/login/?next=%2F" data-icon="google-c" class="link">
        <svg viewBox="0 0 24 24" width="2.5em" height="2.5em" class="icon__1Md2 icon__3F7K">
          <path fill-rule="evenodd"
                d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm.044-5.213c2.445 0 4.267-1.551 4.556-3.781v-1.891h-4.519v1.89h2.602a2.893 2.893 0 0 1-2.724 1.93c-1.194 0-2.677-1.1-2.677-2.843 0-1.621 1.161-2.876 2.677-2.876.739 0 1.413.279 1.922.736l1.399-1.376a4.744 4.744 0 1 0-3.236 8.212z"></path>
        </svg>
      </a>
        <a href="https://leetcode.com/accounts/github/login/?next=%2F" data-icon="github-c" class="link">
          <svg viewBox="0 0 24 24" width="2.5em" height="2.5em" class="icon__1Md2 icon__3F7K">
            <path fill-rule="evenodd"
                  d="M12 2C6.475 2 2 6.475 2 12a9.994 9.994 0 0 0 6.838 9.488c.5.087.687-.213.687-.476 0-.237-.013-1.024-.013-1.862-2.512.463-3.162-.612-3.362-1.175-.113-.288-.6-1.175-1.025-1.413-.35-.187-.85-.65-.013-.662.788-.013 1.35.725 1.538 1.025.9 1.512 2.338 1.087 2.912.825.088-.65.35-1.087.638-1.337-2.225-.25-4.55-1.113-4.55-4.938 0-1.088.387-1.987 1.025-2.688-.1-.25-.45-1.275.1-2.65 0 0 .837-.262 2.75 1.026a9.28 9.28 0 0 1 2.5-.338c.85 0 1.7.112 2.5.337 1.912-1.3 2.75-1.024 2.75-1.024.55 1.375.2 2.4.1 2.65.637.7 1.025 1.587 1.025 2.687 0 3.838-2.337 4.688-4.562 4.938.362.312.675.912.675 1.85 0 1.337-.013 2.412-.013 2.75 0 .262.188.574.688.474A10.016 10.016 0 0 0 22 12c0-5.525-4.475-10-10-10z"></path>
          </svg>
        </a><a href="https://leetcode.com/accounts/facebook/login/?next=%2F" data-icon="facebook" class="link">
          <svg viewBox="0 0 24 24" width="2.5em" height="2.5em" class="icon__1Md2 icon__3F7K">
            <path fill-rule="evenodd"
                  d="M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2 2 6.477 2 12s4.477 10 10 10zm2.52-14.923v1.686h-1.004c-.366 0-.613.077-.74.23-.128.153-.192.383-.192.69v1.207h1.871l-.249 1.891h-1.622v4.849h-1.955V12.78H9v-1.89h1.629V9.497c0-.792.221-1.407.664-1.843.443-.437 1.033-.655 1.77-.655.626 0 1.111.026 1.456.077z"></path>
          </svg>
        </a><a class="ant-dropdown-link ant-dropdown-trigger dropdown__2g7h">
          <svg viewBox="-4 -4 108 108" width="2.5em" height="2.5em" class="link">
            <path xmlns="http://www.w3.org/2000/svg"
                  d="M50 5C25.147 5 5 25.147 5 50s20.147 45 45 45 45-20.147 45-45S74.853 5 50 5zM33.125 55.625a5.624 5.624 0 1 1 0-11.25 5.624 5.624 0 1 1 0 11.25zm16.875 0a5.624 5.624 0 1 1 0-11.25 5.624 5.624 0 1 1 0 11.25zm16.875 0a5.624 5.624 0 1 1 0-11.25 5.624 5.624 0 1 1 0 11.25z"></path>
          </svg>
        </a></div>
    </form>
  </div>
</template>

<script>
export default {
  name: "hw3"
}
</script>

<style scoped>
  body {
    margin: 0;
    padding: 0;
    font-size: 13px;
    font-family: sans-serif;
    background: #eceff1;
  }

  img {
    height: 77px;
    margin-bottom: 35px;
  }

  .box {
    width: 400px;
    padding: 40px 0 33px 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: white;
    text-align: center;
    border-radius: 3px;
    border: 1px solid #eeeeee;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
  }

  .box input[type="text"],
  .box input[type="password"] {
    background: white;
    border: 1px solid #212121;
    display: block;
    margin: 20px auto;
    text-align: left;
    padding: 15px 10px;
    width: 320px;
    outline: none;
    color: black;
    border-radius: 3px;
    transition: 0.25s;
  }

  .box button[type="submit"] {
    border: 0;
    background: linear-gradient(35deg, #546e7a, #37474f);
    display: block;
    margin: 20px auto;
    text-align: center;
    padding: 15px 140px;
    outline: none;
    color: white;
    border-radius: 3px;
    transition: 0.25s;
    cursor: pointer;
  }

  .box p {
    color: black;
  }

  .box a {
    font-size: 12px;
    color: gray;
    text-decoration: underline;
  }

  .actions {
    display: flex;
    align-items: center;
    padding: 5px 30px;
    color: #546e7a;
    font-size: 14px;
    line-height: 20px;
    cursor: pointer;
  }

  .actions a {
    font-size: 12px;
    text-decoration: none;
  }

  .actions span {
    display: inline-block;
    margin-left: 190px; /* 元素1和元素2之間的距離 */
  }

  .link {
    color: #bdbdbd;
    margin: 0 8px;
  }
</style>