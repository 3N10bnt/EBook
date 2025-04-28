# EBook

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Journey Through Fiction and Non-Fiction</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --sage-green: #a8bfa1;
            --earth-brown: #8d6748;
            --soft-orange: #f6c28b;
            --white: #ffffff;
            --light-bg: #f9f9f6;
        }

        body {
            background-color: var(--light-bg);
            font-family: 'Poppins', sans-serif;
            margin: 20px;
            color: #4e4e4e;
            line-height: 1.7;
        }
        h1, h2 {
            text-align: center;
            color: var(--earth-brown);
            font-weight: 600;
        }
        p.intro {
            text-align: center;
            max-width: 750px;
            margin: 0 auto 30px;
            font-size: 1.1em;
            color: #6d6d6d;
        }
        nav.toc {
            background-color: var(--white);
            border: 2px solid var(--sage-green);
            border-radius: 10px;
            padding: 20px;
            max-width: 600px;
            margin: 30px auto;
            box-shadow: 0px 2px 10px rgba(0,0,0,0.05);
        }
        nav.toc ul {
            list-style-type: none;
            padding: 0;
        }
        nav.toc li {
            margin-bottom: 10px;
        }
        nav.toc a {
            color: var(--earth-brown);
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav.toc a:hover {
            color: var(--soft-orange);
        }
        hr {
            border: 0;
            height: 2px;
            background: var(--sage-green);
            width: 80px;
            margin: 30px auto;
        }
        section {
            margin-bottom: 50px;
        }
        ol {
            max-width: 800px;
            margin: 0 auto;
            padding: 0;
            list-style-type: decimal;
        }
        li {
            background-color: var(--white);
            margin-bottom: 15px;
            padding: 15px 20px;
            border-radius: 12px;
            border-left: 5px solid var(--sage-green);
            box-shadow: 0px 3px 8px rgba(0,0,0,0.05);
            transition: background-color 0.3s, transform 0.3s;
        }
        li:hover {
            background-color: var(--soft-orange);
            transform: translateY(-3px);
        }
        a.book-link {
            color: var(--earth-brown);
            text-decoration: none;
            font-weight: 600;
        }
        a.book-link:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            margin-top: 60px;
            font-size: 0.9em;
            color: #a0a0a0;
        }
    </style>
</head>

<body>

    <h1>A Journey Through Fiction and Non-Fiction</h1>
    <p class="intro">
        Welcome to a curated collection of inspiring, thought-provoking, and timeless books across both Fiction and Non-Fiction genres.
        Discover stories and knowledge that nurture your mind, just like fresh produce nurtures the body.
    </p>

    <nav class="toc">
        <h2>Explore</h2>
        <ul>
            <li><a href="#fiction">Fiction Books</a></li>
            <li><a href="#nonfiction">Non-Fiction Books</a></li>
        </ul>
    </nav>

    <hr>

    <section id="fiction">
        <h2>Fiction Books</h2>
        <ol>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/18405.Gone_with_the_Wind" target="_blank">Gone with the Wind by Margaret Mitchell</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/4395.The_Grapes_of_Wrath" target="_blank">The Grapes of Wrath by John Steinbeck</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/5907.The_Hobbit" target="_blank">The Hobbit by J.R.R. Tolkien</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/234225.Dune" target="_blank">Dune by Frank Herbert</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/38447.The_Handmaid_s_Tale" target="_blank">The Handmaid's Tale by Margaret Atwood</a></li>
        </ol>
    </section>

    <hr>

    <section id="nonfiction">
        <h2>Non-Fiction Books</h2>
        <ol>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/29780253-born-a-crime" target="_blank">Born a Crime: Stories from a South African Childhood by Trevor Noah</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/31138556-homo-deus" target="_blank">Homo Deus: A Brief History of Tomorrow by Yuval Noah Harari</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/3106120-the-omnivore-s-dilemma" target="_blank">The Omnivore's Dilemma by Michael Pollan</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/7445.The_Glass_Castle" target="_blank">The Glass Castle by Jeannette Walls</a></li>
            <li><a class="book-link" href="https://www.goodreads.com/book/show/586.The_Right_Stuff" target="_blank">The Right Stuff by Tom Wolfe</a></li>
        </ol>
    </section>

    <footer>
        © 2025 | Compiled with love for curious minds and healthy souls.
    </footer>

</body>
</html>
