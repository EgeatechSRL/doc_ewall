---
title: Vendor Change
description: Getting started with Jigsaw's docs starter template is as easy as 1, 2, 3.
extends: _layouts.documentation
section: content
---

# Vendor Change {#vendor-change}

laravel\vendor\mohamedsabil83\filament-forms-tinyeditor\src\FilamentFormsTinyeditorServiceProvider.php

    // Js::make('tinymce', 'https://cdn.jsdelivr.net/npm/tinymce@5.10.7/tinymce.min.js'),
    Js::make('tinymce', asset('vendor/filament-forms-tinyeditor/tinymce/tinymce.min.js')),