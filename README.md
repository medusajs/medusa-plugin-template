# Plugins

The purpose of this guide is to give an introduction to the structure of a plugin and the steps required to create one. It builds upon our article describing the process of [adding custom functionality](https://docs.medusa-commerce.com/tutorial/adding-custom-functionality). It can be seen as the proceeding steps for extracting your custom functionality to a reusable package for other developers to use.

## What is a plugin?

Plugins offer a way to extend and integrate the core functionality of Medusa.

In most commerce solutions, you can extend the basic features but it often comes with the expense of having to build standalone web applications. Our architecture is built such that plugins run within the same process as the core eliminating the need for extra server capacity, infrastructure and maintenance. As a result, the plugins can use all other services as dependencies and access the database.