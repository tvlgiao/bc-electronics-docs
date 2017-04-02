# Customization

This page will explain all configuration available and how to edit each section appear on theme. Let's view the first homepage.

![Homepage showing full sections](img/home2.jpg)







## Top Banner

![Top Banner](img/home1-top-banner.png)

The top banner can be showed / edited in admin page > __Marketing__ > __Banners__. When you add / edit remember to choose __Location__ is __Top of Page__.

### Colors Customization

To customize colors of this section, go to admin page > __Storefront Design__ > __My Themes__, click button __Customize__ of the current theme to open the Theme Editor. 

![Click customize theme](img/click-customize-theme.png)

Look into the options showing below:

![Theme editor top banner](img/theme-editor-top-banner.png)



## Header

### Header Styles
This theme support 2 different header styles:
- Logo at left
- Logo at right

![Header Logo at left](img/home1-header-left.png)

![Header Logo at right](img/home1-header-right.png)

To configure, open the __Theme Editor__, scroll down to section __Logo__, click to expand the logo options. Choose a certain option of __Logo position__, then click __Refresh__ button appear after.

![Change logo position](img/change-logo-position.png)

### Edit top header text
![Header info text](img/home1-infobar.png)

Edit content in the language file, from admin page > __Storefront Design__ > __My Themes__, click button __Advanced__ > __Edit Theme Files__ of the current theme:

![Edit theme files](img/edit-theme-files.png)

From the left navigation, click to edit the language file (e.i `en.json`):

![Edit language file](img/edit-language-top-info-text.png)

Edit the text as figured above.


### Colors Customization

To customize colors of the header section, look into the options showing below in the Theme Editor:

![Theme editor header](img/theme-editor-header.png)


## Hot News

![Hot news](img/home1-hotnews.png)

This section automatically shows heading of latest posts from your blog.

You can edit or remove this section in template file `templates/pages/home.html`:

![Edit hot news in home.html](img/edit-file-home-hotnews.png)





## Social Icons

![Social icons](img/home1-social-icons.png)

Drag and drop social media icons you want to display in admin page > __Storefront Design__ > __Design Options__:

![Edit social media icons](img/edit-social-media-icons.png)

You can remove this section by editing template file `templates/pages/home.html`:

![Edit social icons in home.html](img/edit-file-home-socialicons.png)


## Main Slideshow / Carousel

![Home 1 Main Carousel](img/home1-main-carousel.jpg)

### Edit the slideshow

Edit the slideshow in admin page > __Storefront Design__ > __Design Options__:

![Edit homepage carousel](img/edit-homepage-carousel.png)


### Colors Customization

To customize color of the slideshow's elements, look into section __Carousel__ in the Theme Editor:

![Theme editor carousel](img/theme-editor-carousel.png)

### Hide the slideshow

To hide the slideshow on homepage, uncheck on the checkbox __Show Carousel__ in section __Carousel__ of the Theme Editor.



## New / Featured / Popular Products

The theme supports 4 layout type of __New Products__, __Featured Products__ and __Popular Products__ blocks:

__Grid__:

![Products Grid](img/home1-products-grid.jpg)

__Carousel__:

![Products Carousel](img/home1-products-carousel.jpg)

__List__:

![Products List](img/home1-products-list.jpg)


### Configure a Layout Type of products block & Number of Products to show up

In the __Theme Editor__ > __Homepage__, look into __New Products__ section (or __Featured Products__, __Most Popular Products__):

- __Display type__: Choose appropriate layout type (__Grid__, __Carousel__, __Left Column__ or __Right Column__).
- __Number of Products__: Choose number of products to show up.

![Theme editor homepage products options](img/theme-editor-homepage-products-options.png)

### Show/Hide Quickview button

When hover on a product item, Quickview button is showed up by default. To disable this feature, uncheck the checkbox __Show Quickview__ in the __Theme Editor__ > __Products__ section.

![Theme editor show/hide Quickview button](img/theme-editor-quickview.png)

### Change colors and image sizes

In the __Theme Editor__ > __Products__ section, Look into the color options below __Product cards__, __Product Sale Badges__, __Product cards (Quick search)__ and __Image sizes__'s options.

![Theme Editor Product Cards options](img/theme-editor-product-cards.png)
![Theme Editor Product Sale Badges options](img/theme-editor-product-sale-badges.png)
![Theme Editor Product Cards Quick Search options](img/theme-editor-product-cards-quick-search.png)
![Theme Editor Image Sizes options](img/theme-editor-image-sizes.png)

### Change the heading text

To change the heading text (New Products, Featured Products, Most Popular Products), edit the language file, look for the key `products` > `new` or `featured` or `top`.

![Edit language new products heading text](img/edit-language-products-new.png)








## New / Featured / Popular Products Tabs

![Special products tabs](img/home1-special-products-tabs.jpg)

This section allows you to display __new products__, __featured products__, and __bestselling products__ in tabs. Products can be displayed as grid, list or carousel depend on configuration in the Theme Editor.

![products options](img/theme-editor-homepage-products-options.png)





## Categories List

![Categories List](img/home1-categories-list.jpg)

This section lets you show categories list, category images and number of products per category.

To edit text of this section, edit the language file `en.json`, find key `emthemesmodez` > `categories_grid`:

![Edit language of categories grid section](img/edit-language-categories-grid.png)

- `heading`: is section title.
- `products_count`: is the translation text showing number of products in category.






## Products by Category

![Products by category](img/home1-products-by-category.jpg)

This section displays products in a specific category. You can display this section type up to 3 sections, represent 3 different categories.

To specify which category to display, edit the language file `en.json`, find keys `emthemesmodez` > `products_by_category`:

![Edit language products by category](img/edit-language-products-by-category.png)

- `category_id_1` to `category_id_3`: represent category ID of products of 3 section instances.
- `heading_image_1` to `heading_image_3`: is image URLs above Hot Categories.
- `subcategory_title_1` to `subcategory_title_3`: is custom heading text of subcategories list.

The large image is  category image.

To find category ID of a certain category, go to admin page > __Products__ > __Product Categories__, click on a category to edit. Now look at the URL on your browser, the ID is appear in the URL as showing below:

![Find category ID](img/find-category-id.png)








## Products by Category with sorting tabs

![Products by category with sorting tabs](img/home1-products-by-category-sorting-tabs.jpg)

This section displays products in a specific category. The tabs let you sorting products by bestselling, featured, new products and top reviewed. You can display this section type up to 3 sections, represent 3 different categories.

To specify which category to display, edit the language file `en.json`, find keys `emthemesmodez` > `products_by_category_sorting_tabs`:

![Edit language products by category](img/edit-language-products-by-category-sorting-tabs.png)

- `bestselling`, `featured`, `new`, `reviews`: are tab title for sorting products by bestselling, fatured, new and top reviewed.
- `view_all`: is text of view all products link.
- `category_id_1` to `category_id_3`: is category ID of each section instance.






## Products by Category with subcategory tabs

__Root category:__

![Products by root category with subcategory tabs](img/home1-products-by-root-category-subcategory-tabs.jpg)

__Sub category:__

![Products by category with subcategory tabs](img/home1-products-by-category-subcategory-tabs.jpg)

This section displays products in a specific category. The tabs let you sorting products by bestselling, featured, new products and top reviewed. You can display this section type up to 3 sections, represent 3 different categories.

To specify which category to display, edit the language file `en.json`, find keys `emthemesmodez` > `products_by_category_subcategories_tabs`:

![Edit language products by category](img/edit-language-products-by-category-subcategory-tabs.png)

- `heading`: is the heading text to display if category is root.
- `view_all`: is text of view all products link.
- `category_id_1` to `category_id_3`: is category ID of each section instance. Set value = `0` to display root category.










## Image Banners

Theme supports many banner styles:

### Fullwidth Banner
![Fullwidth banner](img/home1-fullwidth-banner.jpg)

Support displaying up to 5 fullwidth banners on homepage.

To edit these banners, edit the language file `en.json`, find keys `emthemesmodez` > `banners` > `one_1` to `one_3` represent 3 fullwidth banners accordingly.

![Edit fullwidth banners](img/edit-language-banner-fullwidth.png)

- `title`: is banner title text. Leave a single space character to hide it.
- `text`: is description text. Leave a single space character to hide it.
- `button`: is button text. Leave a single space character to hide it.
- `image`: is banner image URL.
- `url`: is banner link.


### 2 Half Banners

![Half size banners](img/home1-banner-half.jpg)

Support displaying up to 3 half-size banners on homepage.

To edit these banners, edit the language file `en.json`, find keys `emthemesmodez` > `banners` > `half_1` to `half_3` represent 3 fullwidth banners accordingly.

![Edit fullwidth banners](img/edit-language-banner-half.png)


### 2/3 & 1/3 Banners

![2/3 & 1/3 banners](img/home1-banner-2313.jpg)

Support displaying up to 3 half-size banners on homepage.

To edit these banners, edit the language file `en.json`, find keys `emthemesmodez` > `banners` > `twothird_onethird_1` to `twothird_onethird_3` represent 3 fullwidth banners accordingly.

![Edit 2/3 & 1/3 banners](img/edit-language-banner-2313.png)


### 3 Banners

__Default style:__

![3 banners](img/home1-banner-third-2.jpg)


__Boxed style:__

![3 banners](img/home1-banner-third.jpg)


Support displaying up to 3 half-size banners on homepage.

To edit these banners, edit the language file `en.json`, find keys `emthemesmodez` > `banners` > `onethird_x3_1` to `onethird_x3_3` represent 3 fullwidth banners accordingly.

![Edit fullwidth banners](img/edit-language-banner-third.png)







## Image Carousel

![Image carousel](img/home1-image-carousel.png)

To edit image and links in this image carousel section, edit the language file, find key `emthemesmodez` > `image_carousel`

![Edit language image carousel](img/edit-language-brands-carousel.png)

- `image*`: is link to the image.
- `title*`: is image text description.
- `url*`: is image link. Leave a single space letter in the value if you want to hide any image.






## Footer - About Us

Show or hide this section in Theme Editor > __Footer__ section:

![Theme editor footer about us](img/theme-editor-footer-aboutus.png)

You can customize text in the language file `en.json`:

![Edit language footer about us](img/edit-language-footer-about.png)


## Footer - Recent Posts

Show, hide or configure number of post items to display in Theme Editor > __Footer__ section:

![configure footer recent posts](img/theme-editor-footer-blog.png)

To change the heading text, read more text and date format, edit the language file. Find the key `blog` > `recent_posts`, `posted_by` and `label`, edit its values as you want.

![Edit recent blog text in the language file](img/edit-language-blog.png)



## Footer - Newsletter Form

Show or hide this section in Theme Editor > __Footer__ section:

![Configure newsletter form at footer](img/theme-editor-newsletter.png)

To edit text in newsletter form, edit the language file `en.json`, find key `newsletter`, edit text in this section:

![Edit language newsletter](img/edit-language-newsletter.png)


## Footer - Social media icons

Show or hide social media icons in Theme Editor > __Social media icons__ section:

![Configure social icons at footer](img/theme-editor-footer-social-icons.png)

Drag and drop social media icons you want to display in admin page > __Storefront Design__ > __Design Options__:

![Edit social media icons](img/edit-social-media-icons.png)







## Footer - Custom Links

Show or hide custom link groups in Theme Editor > __Footer__ section:

![Footer custom links](img/theme-editor-footer-custom-links.png)

To edit text and links in this footer section, edit the language file, find keys `footer`, 4 keys `links_col_1`, `links_col_2`, `links_col_3`, `links_col_4` represent 4 link columns:

![Edit language file for footer custom links](img/edit-language-footer-custom-links.png)

- `heading`: is heading title in each column.
- `title`: is link label. Leave a single space character to hide this link.
- `url`: is link URL.



## Footer - Page Links

Show, hide or configure number of page links in footer in Theme Editor > __Footer__ section:

![Footer page links](img/theme-editor-footer-pages.png)

This section will show all our page links. To change the heading text __Navigate__, edit the language file `en.json`, find key `footer` > `navigate`, change this key value:

![Edit language file for footer page links heading](img/edit-language-footer-page-links.png)




## Footer - Category Links

Show, hide or configure number of category links in footer in Theme Editor > __Footer__ section:

![Footer category links](img/theme-editor-footer-categories.png)

Edit heading text __Categories__ in the language file `en.json`, find key `footer` > `categories`:

![Edit language for footer categories](img/edit-language-footer-categories.png)




## Footer - Contact Info

Show or hide this section in Theme Editor > __Footer__ section:

![Footer contact info](img/theme-editor-footer-contact-info.png)

Edit heading text __Contact Info__ in the language file `en.json`, find key `footer` > `info`:

![Edit language for footer contact info](img/edit-language-footer-contact-info.png)

- `call_us`: is the translation text for phone calling number.
- `email`: is email to display.

Address can be edited in admin page > __Store Setup__ > __Store Profile__ > __Store Address__.






## Footer - Location

Show or hide this section in Theme Editor > __Footer__ section:

![Footer location](img/theme-editor-footer-location.png)

Edit heading text __Contact Info__ and the image in the language file `en.json`, find key `footer`, change value of `location` and `location_image`:

![Edit language for footer location](img/edit-language-footer-location.png)




## Footer - Popular Brands

Show or hide this section in Theme Editor > __Footer__ section:

![Footer brands](img/theme-editor-footer-brands.png)

Edit heading text __Popular Brands__ in the language file `en.json`, find key `footer` > `brands`:

![Edit language for footer brands](img/edit-language-footer-brands.png)




## Footer - Payment Icons

![Theme editor payment icons](img/theme-editor-payment-icons.png)

To show/hide payment icons, go to Theme __Editor__ > __Payment Icons__ secitons, check or uncheck any icons you want to show or hide.




## Footer - Credit Links

![Theme editor credit links](img/theme-editor-credits.png)

To show/hide the credit links, go to Theme Editor > __Footer__ section, tick or untick the checkboxes as showing above.


## Customize footer colors

![Theme editor footer top colors](img/theme-editor-footer-top-colors.png)

![Theme editor footer bottom colors](img/theme-editor-footer-bottom-colors.png)


![Theme editor footer copyright colors](img/theme-editor-footer-copyright-colors.png)




## Edit homepage template

This chapter will instruct you how to customize homepage layouts, show, hide or rearrange sections from different theme styles.

For example, if you want to use theme __Default__ style as the main theme, but also want to display other content blocks from __Full__ style. You can edit the template files, rearrange, add more content blocks or delete unused content blocks.

Let open folder `templates` > `components` > `emthemes-modez` > `home` in the template files editor:

![Edit template file home default](img/edit-file-home-default.png)

There is 2 files in this folder:

- `default.html`: is used for __Default__ style.
- `full.html`: is used for __Full__ style.

Let's take a look at contents of 2 files:

__default.html__

```plain
{{> components/emthemes-modez/sections/section section="banner_3x_1"}}
{{> components/emthemes-modez/sections/section section="special_products_tabs"}}
{{> components/emthemes-modez/sections/section section="banner_3x_2"}}
{{> components/emthemes-modez/sections/section section="products_by_category_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_2"}}
{{> components/emthemes-modez/sections/section section="banner_one_1"}}
{{> components/emthemes-modez/sections/section section="banner_half_1"}}
{{> components/emthemes-modez/sections/section section="images_carousel"}}
```

__full.html__

```plain
{{> components/emthemes-modez/sections/section section="new_products"}}
{{> components/emthemes-modez/sections/section section="featured_products"}}
{{> components/emthemes-modez/sections/section section="popular_products"}}
{{> components/emthemes-modez/sections/section section="special_products_tabs"}}
{{> components/emthemes-modez/sections/section section="categories_grid"}}
{{> components/emthemes-modez/sections/section section="banner_3x_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_2"}}
{{> components/emthemes-modez/sections/section section="products_by_category_3"}}
{{> components/emthemes-modez/sections/section section="banner_3x_2"}}
{{> components/emthemes-modez/sections/section section="products_by_category_sorting_tabs_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_sorting_tabs_2"}}
{{> components/emthemes-modez/sections/section section="products_by_category_sorting_tabs_3"}}
{{> components/emthemes-modez/sections/section section="banner_one_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_subcategories_tabs_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_subcategories_tabs_2"}}
{{> components/emthemes-modez/sections/section section="products_by_category_subcategories_tabs_3"}}
{{> components/emthemes-modez/sections/section section="banner_half_1"}}
{{> components/emthemes-modez/sections/section section="images_carousel"}}

```

The files are showing very clearly how content blocks are displayed. See values in parameter `section="..."`:

- `new_products`: Is a block contains new products.
- `featured_products`: Is a block contains new featured products.
- `popular_products`: Is a block contains popular (or bestselling) products.
- `special_products_tabs`: Show new products, featured products and bestselling products in tabs.
- `categories_grid`: Showing categories list with image and number of products in grid.
- `banner_3x_1`, `banner_3x_2`, `banner_3x_3`: 3 banner blocks show 3 banner images of each block.
- `banner_one_1`, `banner_one_2`, `banner_one_3`: 3 banner blocks show fullwidth banner image of each block.
- `banner_half_1`, `banner_half_2`, `banner_half_3`: 3 banner blocks show 2 banner images of each block.
- `products_by_category_1`, `products_by_category_2`, `products_by_category_3`: 3 blocks display products by specific category.
- `products_by_category_sorting_tabs_1`, `products_by_category_sorting_tabs_2`, `products_by_category_sorting_tabs_3`: 3 blocks display products by specific category with tabs allow to sort products by bestselling, new products, featured products and top reviewed.
- `products_by_category_subcategories_tabs_1`, `products_by_category_subcategories_tabs_2`, `products_by_category_subcategories_tabs_3`: 3 blocks display products by specific category with subcategory filter in tabs.
- `images_carousel`: Lets you show images in carousel slider.


You can add or delete any section you want, rerrange by move each line up or down.



## Edit footer template

If you want more control about the footer, you can edit the footer template at `templates` > `components` > `common` > `footer.html`:

![Edit footer template](img/edit-file-footer.png)

