<div align="center">

<img src="assets/images/favicon.svg" alt="Homilia" width="50"/>

# Homilia
A free, open-source web template to create a website to advertise your book.

</div>

# Features
- 💎 Zero JS - a lightweight HTML & CSS-only template, free of JavaScript!
- 🛒 Buy Now Link - easily add your Amazon or other links to drive sales!
- 📕 Free Sample Chapter - engage readers by offering an optional sneak peek of your book!
- ⭐ Reader Reviews - highlight glowing testimonials from your audience to build trust!
- 📷 Book Image Gallery - showcase your book with a sleek, user-friendly image gallery!

## Usage
The first step is to click the **Use this template** button to create a new repository, or you can fork the repo.

### Add title & description
Add an SEO-friendly title and description for your website in the [index.html](https://github.com/digitalmalayalistudio/homilia/blob/main/index.html#L7-L9).

```html
<title>Homilia - Open-source Book Promotion Website Template</title>
<meta name="description" content="Homilia is a zero-JS, open-source book promotion website template licensed under MIT.">
```
### Replace the images
You can replace the images in the [assets](assets) folder. 

### Add logo
In the `nav` section of the [index.html](https://github.com/digitalmalayalistudio/homilia/blob/main/index.html#L24-L28) file, you can add the book title as the logo or replace the `h1` with your book title image.

```html
<div class="logo">
    <a class="color-primary" href="#">
        <h1 class="text-center">HOMILIA<br>Open-source<br>Web Template</h1>
    </a>
</div>
```
### Add book description, image and purchase link
In the `main` section of the [index.html](https://github.com/digitalmalayalistudio/homilia/blob/main/index.html#L42-L57) file, you can add an image, a brief description of your book, and an Amazon or other purchase link.

```html
<section class="overview">
    <figure>
        <img src="assets/images/book.webp" alt="Book mockup.">
    </figure>
    <div class="brief">
        <p class="large">Homilia is a zero-JavaScript, HTML-and-CSS-only, open-source book promotion
            <strong>website template</strong> licensed under MIT.
        </p>
        <div class="amazon-sample">
            <a class="amazon" href="#">
                <img src="assets/images/amazon.svg" width="90" alt="Available on Amazon">
            </a>
            <p>Sample chapter? <a class="bold link" href="sample.html">Click here.</a></p>
        </div>
    </div>
</section>
```

### Add detailed book description and author biography
Find the `about` section of [index.html](https://github.com/digitalmalayalistudio/homilia/blob/main/index.html#L58-L94) file to add detailed description about the book and biography of the author.

```html
<section id="about">
    <div class="section-title">
        <hr>
        <h2>
            About
        </h2>
        <hr>
    </div>
    <div class="book-details">
        <h3 class="subtitle">Book</h3>
        <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad facilis quibusdam
            adipisci eos facere, delectus incidunt nesciunt quaerat, ea possimus itaque eveniet nobis quis
            alias fugit fugiat voluptatem ut illo?
            Quis hic numquam delectus eveniet ullam nobis excepturi quas accusantium asperiores ratione
            adipisci, molestiae reprehenderit nostrum optio blanditiis officiis libero maxime vitae, cumque
            tenetur quod rem. Recusandae perferendis eveniet deleniti.
        </p>
        <p><strong>ISBN</strong>: 978-65-4321-012-3</p>
    </div>
    <div class="author-details">
        <h3 class="text-center">Author</h3>
        <div class="author">
            <div class="bio">
                <h4 class="subtitle text-center">John Doe</h4>
                <figure class="author-profile"><img src="assets/images/author.webp" alt="John Doe">
                </figure>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore, nesciunt. Velit
                    repellat illo nobis porro fugiat laborum quod quis, consequuntur, totam culpa ratione
                    nulla pariatur, minus alias magni sit id.
                    Recusandae laudantium quia reprehenderit velit, reiciendis tempore molestias, aliquid
                    officiis ducimus qui exercitationem libero illum consectetur corporis aspernatur.
                    Pariatur ratione ea qui tempora, accusantium quos dolores fugit <a href="#" class="link"
                        target="_blank">asperiores</a> quia vero?</p>
            </div>
        </div>
    </div>
</section>
```
### Add Goodreads and StoryGraph links
Find this inside the `reviews` section of [index.html](https://github.com/digitalmalayalistudio/homilia/blob/main/index.html#L106-L111) file to add Goodreads and StoryGraph links:

```html
<div class="add-review text-center">
    <p>Already read the book?</p>
    <p>Add your review to <a class="link" href="#" target="_blank">The
            StoryGraph</a> or <a href="#" class="link" target="_blank">Goodreads</a>.</p>
</div>
```

### Add reviews
Inside the `review-row` of [index.html](https://github.com/digitalmalayalistudio/homilia/blob/main/index.html#L118-L178) file you can add review, reviewer name and image. Take a note of the `--position:` in the `div` with the class `review`. If you add more than 6 reviews, make sure to change the `--quantity` in [style.css](https://github.com/digitalmalayalistudio/homilia/blob/main/style.css#L397).

```html
<div class="review" style="--position: 1">
    <p class="quote bold">“</p>
    <p class="review-text italic">Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dolorum, numquam porro dolor fugiat consectetur nihil nulla blanditiis incidunt
        reiciendis consequuntur maiores. Nulla iste dolores numquam aliquid vero quos quae
        soluta?
    </p>
    <figure><img class="reviewer" src="assets/images/author.webp" alt="Reviewer">
        <figcaption><strong>James Doe</strong><br>Literary Critic
        </figcaption>
    </figure>
</div>
```

### Add a sample chapter
Inside the `sample-container` of [sample.html](https://github.com/digitalmalayalistudio/homilia/blob/main/sample.html#L50-L110) file, you can add a sample chapter from your book.

```html
<div class="sample-container">
    <h3 class="text-center">John Doe</h3>
    <p class="text-center">Officiis praesentium nulla architecto modi dolor sit amet consectetur,
        adipisicing elit. Odit tempora expedita quasi doloremque quam quas porro libero?
    </p>
    <div class="sample">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, vitae asperiores voluptate
            rem sequi blanditiis! Quaerat illo, reprehenderit ad corrupti facilis suscipit, numquam sunt
            blanditiis quidem eaque dignissimos obcaecati itaque?
            Modi, deserunt illo nihil ullam quaerat facilis, vero unde, possimus harum saepe dolorum
            corrupti! Illum laboriosam itaque nobis consequuntur nulla doloremque, in deleniti possimus
            asperiores. Ut exercitationem cupiditate aperiam odio?
        </p>
        <p>Debitis consequuntur adipisci aliquam provident temporibus ad molestias, quaerat molestiae
            deserunt quae ratione itaque doloremque rerum, assumenda vitae reprehenderit fuga libero
            magnam.
            Voluptates consequuntur voluptas suscipit dolores tempora laboriosam aspernatur commodi fuga
            et, doloribus ab praesentium culpa, quas vero, veritatis corrupti atque voluptatibus.
            Praesentium dignissimos nesciunt perspiciatis, hic quibusdam incidunt earum ullam.
            Pariatur nostrum eius sapiente molestiae earum ipsam voluptate iure. Accusantium distinctio
            sapiente itaque, iste recusandae autem nostrum veniam quae, dolorum in possimus? Nisi quis,
            perspiciatis alias inventore quisquam in ipsa?
        </p>
        <p>Quia velit magnam quasi minus enim quam minima numquam neque quis totam fuga doloremque nisi
            cupiditate, corrupti laudantium consequuntur quo ratione aperiam.
            Ad aliquam beatae repudiandae vel molestias placeat corrupti, facere, cupiditate soluta
            reprehenderit sit minima natus commodi! Cumque sed, odio eius ratione possimus ipsum commodi
            libero, voluptatum blanditiis delectus quis quo.
            A suscipit odit quam facilis, beatae autem iusto, veniam architecto, voluptate culpa eaque
            laborum! Labore iste est, deleniti ullam doloremque officiis eum odit iusto voluptatem
            delectus impedit eius aliquid vel!
        </p>
        <p>Enim quibusdam, optio voluptates neque a perspiciatis molestiae ipsum dicta quo inventore ab,
            recusandae quisquam architecto delectus illo reprehenderit, provident beatae maiores ea
            placeat pariatur! Et architecto sint voluptatum, eveniet animi illo, quas explicabo tenetur
            nobis, saepe voluptas aperiam dolor dolorem ea eligendi repellat consectetur molestias quasi
            inventore laboriosam ipsa! Consequuntur blanditiis ratione nihil quod asperiores rerum
            explicabo eaque officiis illum dignissimos tempore delectus hic, corporis ab id, assumenda
            pariatur, quos in accusantium eligendi? Possimus libero aliquid a amet vel ullam, aut
            molestias vero sed, quos, perferendis nesciunt. Impedit, cupiditate. Sint, architecto.</p>
        <p>Eius delectus numquam dolores maxime consectetur iusto quod eligendi. Quia, accusamus
            voluptates? Quas corrupti odit, dignissimos repudiandae rem illo. Unde eos id molestias
            veritatis excepturi saepe maxime ipsa ab omnis cum soluta itaque reiciendis corrupti rem,
            quas, sit nam! Repudiandae, impedit! Natus laborum neque sunt earum beatae vitae dolorem quo
            provident porro velit minus distinctio deleniti omnis, sapiente fugiat ut perspiciatis odit
            labore reiciendis cumque nam perferendis amet officia voluptatum. Exercitationem ipsa, amet
            eveniet nesciunt cumque ducimus, saepe accusantium totam minima dicta aut cupiditate placeat
            soluta provident aliquam est? Delectus obcaecati, eaque illo odio nisi dolore ab debitis sit
            et?</p>
        <h4 class="text-center">Footnote</h4>
        <p class="italic text-center">Distinctio, soluta consequatur dicta nemo libero repellendus
            repellat quasi dolor. Cum tenetur unde perferendis laudantium officiis praesentium nulla
            earum architecto modi accusamus.
            Itaque corporis quidem sit temporibus ut, ducimus dolorem non qui dolorum adipisci modi
            ratione explicabo quasi architecto ipsam, aperiam asperiores tempore. Totam enim facere
            officia dicta unde voluptas, similique quisquam?
            Aliquid officia quam optio blanditiis, illum aut ex quis mollitia sed explicabo id
            exercitationem excepturi!
        </p>
    </div>
</div>
```

## Credits
- Logo - [Hand with quill](https://openclipart.org/detail/281214/hand-with-quill)
- Badge - [Available at Amazon](https://sellercentral.amazon.com/help/hub/reference/external/200573210)
- Mockup - [Book-Cover-Mockups-TinyDesignr](https://www.mediafire.com/file/b9wnqj5czk2efgh/Book-Cover-Mockups-TinyDesignr.zip)

> [!NOTE]  
> This template is neither associated with nor endorsed by Amazon.

## License
**The MIT License (MIT)**

Copyright (c) 2025 Digital Malayali Studio