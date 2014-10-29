HOWTO
=====

Grab yourself a copy of food-free-at-last-2.html. This is the master file.
Then download Calibre:

  http://calibre-ebook.com/download
  
Run:

    ebook-convert food-free-at-last-2.html food-free-at-last-2.epub \
    --cover food-free-at-last-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup&Dr Robert Jones MD PhD DDS ODD" \
    --language English \
    --series "Food-Free at Last" \
    --series-index 1 \
    --title "Food-Free at Last: How I Learned to Eat Air" \
    --title-sort "Food-Free at Last: How I Learned to Eat Air" \
    --preserve-cover-aspect-ratio
  
or if you're a Kindle user:

    ebook-convert food-free-at-last-2.html food-free-at-last-2.mobi \
    --cover food-free-at-last-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup&Dr Robert Jones MD PhD DDS ODD" \
    --language English \
    --series "Food-Free at Last" \
    --series-index 1 \
    --title "Food-Free at Last: How I Learned to Eat Air" \
    --title-sort "Food-Free at Last: How I Learned to Eat Air" \
    --prefer-author-sort

or if you just want a PDF:

    ebook-convert food-free-at-last-2.html food-free-at-last-2.pdf \
    --cover food-free-at-last-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup&Dr Robert Jones MD PhD DDS ODD" \
    --language English \
    --series "Food-Free at Last" \
    --series-index 1 \
    --title "Food-Free at Last: How I Learned to Eat Air" \
    --title-sort "Food-Free at Last: How I Learned to Eat Air" \
    --paper-size a4 \
    --pdf-add-toc \
    --pdf-page-numbers \
    --preserve-cover-aspect-ratio \
    --margin-bottom 72 \
    --margin-top 72 \
    --margin-left 72 \
    --margin-right 72

Calibre's full command-line interface is documented here:

  http://manual.calibre-ebook.com/cli/ebook-convert.html
