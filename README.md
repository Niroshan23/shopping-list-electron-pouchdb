# Shopping List - with Electron and PouchDB 

<strong style="color:red">Note</strong>: This is a work in progress. 

This Shopping List is an Offline First demo application built using [PouchDB](https://pouchdb.com/) with the Electron framework. [This app is part of a series of Offline First demo apps, each built using a different stack.](https://github.com/ibm-watson-data-lab/shopping-list) 

## Quick Start

1. Clone this GitHub [repo](https://github.com/ibm-watson-data-lab/shopping-list-electron-pouchdb)
2. Run `npm install`
3. Run `npm start`

## Features

Shopping List is a simple demo app, with a limited feature set. Here is a list of features written as user stories grouped by Epic:

* Planning
  * As a \<person planning to shop for groceries\>, I want to \<create a shopping list\> so that \<I can add items to this shopping list\>.
  * As a \<person planning to shop for groceries\>, I want to \<add an item to my shopping list\> so that \<I can remember to buy that item when I am at the grocery store later\>.
  * As a \<person planning to shop for groceries\>, I want to \<remove an item from my shopping list\> so that \<I can change my mind on what to buy when I am at the grocery store later\>.
* Shopping
  * As a \<person shopping for groceries\>, I want to \<view items on my shopping list\> so that \<I can remember what items to buy\>.
  * As a \<person shopping for groceries\>, I want to \<add an item to my shopping list\> so that \<I can remember to buy that item\>.
  * As a \<person shopping for groceries\>, I want to \<remove an item from my shopping list\> so that \<I can change my mind on what to buy\>.
  * As a \<person shopping for groceries\>, I want to \<check off an item on my shopping list\> so that \<I can keep track of what items I have bought\>.
* Offline First
  * As a \<person shopping for groceries\>, I want to \<have the app installed on my device\> so that \<I can continue to utilize my shopping list when no internet connection is available\>.
  * As a \<person shopping for groceries\>, I want to \<have my shopping list stored locally on my device\> so that \<I can continue to utilize my shopping list when no internet connection is available\>.
  * As a \<person shopping for groceries\>, I want to \<sync my shopping list with the cloud\> so that \<I can manage and utilize my shopping list on multiple devices\>.
* Multi-User / Multi-Device
  * As a \<new user\>, I want to \<sign up for the app\> so that \<I can use the app\>.
  * As an \<existing user\>, I want to \<sign in to the app\> so that \<I can use the app\>.
  * As an \<existing user\>, I want to \<sign out of the app\> so that \<I can protect my privacy\>.
* Geolocation
  * As a \<person planning to shop for groceries\>, I want to \<associate a shopping list with a grocery store\> so that \<I can be notified of this shopping list when I am physically at that grocery store\>.
  * As a \<person associating a shopping list with a physical store\>, I want to \<access previously-used locations\> so that \<I can quickly find the physical store for which I am searching\>.
  * As a \<person shopping for groceries\>, I want to \<be notified of a shopping list when I am physically at the grocery store associated with that shopping list\> so that \<I can quickly find the shopping list for my current context\>.

## App Architecture

- https://electron.atom.io/ - Electron
- http://materializecss.com/ - Materialize CSS
- https://pouchdb.com/ - PouchDB library
- https://usecuid.org/ - Collision-resistant ids

## Tutorial

Refer to the [tutorial](tutorial) for step-by-step instructions on how to build your own Offline First shopping list desktop app with Electron and PouchDB.
