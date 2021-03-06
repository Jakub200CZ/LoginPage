# Custom Login page

Login page useing css framework [Tailwind](https://tailwindcss.com/)


## Installation

Download project or copy/paste by this code.

---

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Login Page</title>

    <!--Tailwind Link-->
    <link href="https://unpkg.com/tailwindcss/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&display=swap" rel="stylesheet">


    <!--Custom Backgroud-->
    <style>
        .body-bg {
            background-color: #414141  ;
            background-image: linear-gradient(315deg, #414141   0%, #000000 74%);
        }

        * {
            user-select: none;
        }
    </style>

</head>
<body class="body-bg min-h-screen pt-12 md:pt-20 pb-6 px-2 md:px-0" style="font-family:'Lato',sans-serif;">


    <main class="bg-white max-w-lg mx-auto p-8 md:p-12 my-10 rounded-lg shadow-2xl text-center">
        <section>
            <h3 class="font-bold text-2xl">Log in to your account.</h3>
            <p class="text-gray-600 pt-2">Please do not share or publish your data with anyone, there is a risk of theft.</p>
        </section>

        <section class="mt-5 text-left">
            <form class="flex flex-col" method="POST" action="#">
                <div class="mb-6 pt-3 rounded bg-gray-200">
                    <label class="block text-gray-700 text-sm font-bold mb-2 ml-3" for="email">Email / Username</label>
                    <input type="text" id="email" class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-blue-600 transition duration-300 px-3 pb-3">
                </div>
                <div class="mb-6 pt-3 rounded bg-gray-200">
                    <label class="block text-gray-700 text-sm font-bold mb-2 ml-3" for="password">Password</label>
                    <input type="password" id="password" class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-blue-600 transition duration-300 px-3 pb-3">
                </div>
                <div class="flex justify-end">
                    <a href="#" class="text-sm text-blue-600 hover:text-blue-700 hover:underline mb-6">Forgot your password / username?</a>
                </div>
                <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 rounded shadow-lg hover:shadow-xl transition duration-200" type="submit">Login</button>

                <div class="max-w-lg mx-auto text-center mt-12">
                    <p class="text-gray-600">New user? <a href="#" class="font-bold hover:underline"> Create Account Here</a></p>
                </div>

            </form>
        </section>
    </main>


    <footer class="max-w-lg mx-auto flex justify-center text-white">
        <a href="#" class="hover:underline">Contact</a>
        <span class="mx-3">???</span>
        <a href="#" class="hover:underline">Privacy</a>
        <span class="mx-3">???</span>
        <a href="#" class="hover:underline">Terms of use</a>
    </footer>
</body>
</html>
```

---

## Support 

I will be happy if you support me follow on the mem instagram where I give you the regular content regarding WEB Development 
[CLICK HERE --> @jakub200_cz](https://www.instagram.com/jakub200_cz/)
