<template lang="pug">
nav.navbar.is-spaced
    .container
        .navbar-brand
            a.navbar-item
                img(src="https://laravel.com/img/logotype.min.svg")
            a.navbar-burger
                span
                span
                span
        .navbar-menu
            .navbar-start
                a.navbar-item Home
                a.navbar-item Documentation

.container
    .columns
        .column.is-one-quarter
            aside.menu
                p.menu-label General
                ul.menu-list
                    li
                        a.is-active Dashboard
                    li
                        a Customers
                p.menu-label Administration
                ul.menu-list
                    li
                        a Team Settings
                    li
                        a Manage Your Team
                        ul
                            li
                                a Members
                            li
                                a Plugins
                            li
                                a Add a member
                    li
                        a Invitations
                    li
                        a Cloud Storage Environment Settings
                    li
                        a Authentication
                p.menu-label Transactions
                ul.menu-list
                    li
                        a Payments
                    li
                        a Transfers
                    li
                        a Balance
        .column
            nav.breadcrumb
                ul
                    li
                        a Home
                    li.is-active
                        a Dashboard
            section.hero.is-info.is-small
                .hero-body
                    p.title Hello, Admin.
                    p.subtitle I hope you are having a great day!
            section.section
                .level
                    .level-item.has-text-centered
                        article
                            p.heading Users
                            p.title 439k
                    .level-item.has-text-centered
                        article
                            p.heading Products
                            p.title 59k
                    .level-item.has-text-centered
                        article
                            p.heading Open Orders
                            p.title 3.4k
                    .level-item.has-text-centered
                        article
                            p.heading Exceptions
                            p.title 19
</template>
