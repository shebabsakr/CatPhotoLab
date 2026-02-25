# 🐱 CatPhotoApp

A beginner-friendly web page showcasing cat photos, cat-related lists, and a simple interactive form. Built with HTML and semantic elements.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Demo](#demo)

## Overview
CatPhotoApp is a simple web project where users can:
- View cute cat images with captions.
- Explore lists of things cats love and hate.
- Submit details about their own cats using an interactive form.

The project focuses on **semantic HTML** to ensure accessibility and clean structure.

## Features
- **Cat Photos**: Images with descriptive alt text wrapped in `<figure>` and `<figcaption>`.
- **Cat Lists**:
  - Favorite things (unordered list):
    - catnip
    - laser pointers
    - lasagna
  - Things cats hate (ordered list):
    1. flea treatment
    2. thunder
    3. other cats
- **Interactive Form**:
  - Indoor/outdoor status (radio buttons)
  - Personality traits (checkboxes)
  - Cat photo URL (text input)
  - Submit button
- **Accessible Design**: Proper labeling for inputs and images.
- **External Links**: Open in a new tab when necessary.

## Technologies Used
- HTML5
- Semantic HTML: `<main>`, `<section>`, `<figure>`, `<figcaption>`
- Forms: `<form>`, `<fieldset>`, `<legend>`, `<input>`, `<button>`
- Lists: `<ul>` and `<ol>`

## How It Works
Users can browse cat images and lists, then submit information about their own cats. The form ensures accessibility through proper labeling and required fields, like a cat photo URL. Submitted data is sent to a demo endpoint:
