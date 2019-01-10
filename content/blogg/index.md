---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
Dagens Bild
===========================

Dagens bild är en blogg som jag har skapat där iden är att jag ska lägga ut en bild varje dag på något nytt och spännande.
Om jag känner mig själv så lär det inte komma ut så många inlägg men jag ska göra mitt bästa.