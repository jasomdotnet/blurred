# blurred
Module for Drupal 7 blurring background for uploaded images while keeps desired aspect ratio. Creates thumbnails for portrait (vertical) pictures as if they were landscape (vertical) and vice versa. 

This is copy of fully functioning module from Drupal module repository. I have created it back in 2016 because native Drupal 7 mechanism around thumbnails didn't fit my needs: when user uploads photos taken by mobile, thumbs are terrible.

![Blurred background module for Drupal 7](https://www.drupal.org/files/project-images/blurred.jpg)

## Maintainers
[Jasom Dotnet](https://www.drupal.org/user/290309)      

## Project homepage
[Project homepage](https://www.drupal.org/sandbox/jasom/2801585)

## Installation
* Install as usual
* Set 'scale' effect for 'thumbnail image style' to 256x144 (upscaling allowed)
* Set 'blurred' effect for 'thumbnail image style' to 256x144
* Flush 'thumbnail image style' images (`drush image-flush thumbnail`)
 
## Credits
* [Jasom Dotnet](https://www.drupal.org/user/290309)
* [drupalfan79](https://www.drupal.org/user/1189154)