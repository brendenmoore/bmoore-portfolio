---
layout: "../../layouts/BlogPost.astro"
title: "YNAB Currency Converter"
description: "Web App that integrates with the YNAB public API for easy currency conversion"
pubDate: "July 2022"
# heroImage: "/placeholder-hero.jpg"
technologies: 
    - React
    - MUI
    - NextJS
    - Typescript
    - React-Query
    - YNAB API
---

This was a fun side project made at the request of my sister and brother-in-law who currently live in Europe. We use a budgeting app called [YNAB](https://youneedabudget.com) which is an absolute joy to use. However, you can only designate one currency to use within your budget. Sometimes my sister would make a purchase in US Dollars and want to enter that transaction in the app. There is currently no way to do that without going elsewhere and converting it to Euros first.

With this utility, you can enter a transaction and it will convert it automatically and the use the YNAB API to add the transaction to your account.

I am using OAuth 2 to authenticate the user with their YNAB account.

A YNAB account required to use the app, unfortunately. I should put some screenshots on here to demonstrate it.

Github link: https://github.com/brendenmoore/ynab-currency-converter

Live Project: https://ynab.bmoore.dev