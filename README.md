# [Stellar dreams](https://stellardreams.github.io/)

## Docs

### Adding new post

Posts are stored in the `_posts` directory and named according to the `YEAR-MONTH-DAY-title.MARKUP` format as per [the usual](https://jekyllrb.com/docs/posts/).

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. For example, the following are examples of valid post filenames:

```
2020-07-20-writing-jekyll-posts.md
```

##### Sample post content
```
---
title: "Post: Standard"							# post title
excerpt_separator: "<!--more-->"				# post excerpt separator
categories:										# categories item
  - Post Formats
tags:											# categories item
  - Post Formats
  - readability
  - standard
---

All children, except one, grow up. They soon know that they will grow up, and the way Wendy knew was this. One day when she was two years old she was playing in a garden, and she plucked another flower and ran with it to her mother. I suppose she must have looked rather delightful, for Mrs. Darling put her hand to her heart and cried, "Oh, why can't you remain like this for ever!" This was all that passed between them on the subject, but henceforth Wendy knew that she must grow up. You always know after you are two. Two is the beginning of the end.

Mrs. Darling first heard of Peter when she was tidying up her children's minds. It is the nightly custom of every good mother after her children are asleep to rummage in their minds and put things straight for next morning, repacking into their proper places the many articles that have wandered during the day.

<!--more-->

If you could keep awake (but of course you can't) you would see your own mother doing this, and you would find it very interesting to watch her. It is quite like tidying up drawers. You would see her on her knees, I expect, lingering humorously over some of your contents, wondering where on earth you had picked this thing up, making discoveries sweet and not so sweet, pressing this to her cheek as if it were as nice as a kitten, and hurriedly stowing that out of sight. When you wake in the morning, the naughtiness and evil passions with which you went to bed have been folded up small and placed at the bottom of your mind and on the top, beautifully aired, are spread out your prettier thoughts, ready for you to put on.
```

Check out `_posts` directory for more  sample post

### Adding Pages and Updating

Pages are stored in the `_page` directory

#####  Sample `about.md` page

```
---
permalink: /about/										# page url
title: "About" 											# page title
excerpt: "My about page"								# page description
last_modified_at: 2020-05-01T10:15:22-04:00 			# page modified date
toc: true												# table of content is set to true
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error repellendus architecto repellat culpa porro minus nemo, eos voluptas obcaecati beatae at dicta? Aut illum dignissimos voluptas unde nemo, eaque nihil porro beatae molestias magni libero nam! Cum unde numquam corrupti ipsum debitis eos nihil optio totam fuga provident ipsa similique, voluptate officiis.

# What I do

Placeat ipsam, asperiores optio accusantium nam autem nisi explicabo eveniet eum atque! Repellendus aut distinctio mollitia recusandae eaque veniam voluptatum quam quae ad, ipsam hic libero qui natus autem nobis similique eos, nam a rem provident, veritatis illum reprehenderit? Eos ducimus repudiandae aspernatur, voluptatum velit cupiditate, earum nostrum temporibus. Magnam amet tempore repellat minus at voluptate earum, error soluta possimus impedit ad voluptas molestias, quasi corrupti natus autem nam illum quibusdam quam assumenda repudiandae quidem ipsam! Rem officia libero est quasi mollitia voluptates repellat enim voluptatibus aliquam veniam.

## Team

Fugit facilis sit ducimus, voluptas adipisci explicabo beatae ea eligendi qui odio iure eveniet non delectus voluptate, expedita incidunt accusamus! Recusandae molestias enim, perspiciatis corporis reiciendis doloremque voluptates neque eligendi incidunt placeat laboriosam fugit nostrum deserunt veniam quia nemo perferendis. Hic et labore modi aspernatur nisi.
```

## Development

To set up your environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000//`. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.