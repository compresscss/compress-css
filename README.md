# Compress CSS – Online CSS Minifier

CompressCSS is a free tool that you can use to minify your CSS files online.
Smaller file size means less bandwidth consumption, so by compressing you're
not only saving up money on hosting but you're also making your site load faster.

## How does it work?
It works by removing unnecessary white-spaces, line breaks, indentations, comments, semicolons, quotes and by combining rules when possible. It can also optimize various properties, like converting rgb colors to shorthand hex equivalent resulting into shorter code. By the default, the compressor also removes all invalid CSS such as negative paddings and empty rules. These are just a few among many things that this tool can do.

CompressCSS uses a modified version of Clean-CSS for all CSS minification. Based on benchmarks, it is currently the best when it comes to reducing the file size of CSS files.

## Usage
1. First we recommend that you create a backup of your original CSS file. After that, head to https://compresscss.net/
2. Place your CSS code inside the input box (left side). Make sure to NOT include <style> tags.
3. Click "Compress" and wait for it to finish the process.
4. Once finished, the compressed CSS codes should appear in the output box (right side).

## Preserved
You can use the comment tag with exclamation mark to keep an important comment or to ignore that part when compressing. To use, put the content between `/*!` and `*/`.

Example:
```/*! CompressCSS | MIT License | Do not remove */```
