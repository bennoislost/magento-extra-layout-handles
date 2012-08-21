#H&O Handles
This is a utility module that should make building Magento websites a bit easier.

## Add handles to category page

If you are viewing a category:
/products/dvds.html (category id: 5)

You'll get a handle by default:
```
CATEGORY_5
```

We add the following:
```
CATEGORY_2_child_child
```
Category 2 is the root category for this store, so allows for store specific configuration

```
CATEGORY_2_child_dvds
```
This one is kinda cool, this one allows you have one layout for multiple childcategories. Imagine the following categories:
- /playgroup/books.html
- /kindergarten/books.html
- /elementary/books.html

All these categories will have the `CATEGORY_2_child_books` handle.

```
CATEGORY_3_child
```
Child of a certain category.

```
CATEGORY_3_dvds
```
This one probably is kinda useless, but is the current category written in a different notation.


## Add attribute set handle to product page

```
PRODUCT_ATTRIBUTE_SET_default
```
For styling based on the attribute set handle.

## Add handles to CMS page
If you have the page: customerservice/faq/question_one, you'll get the following handles:

```
CMS_PAGE_customerservice_child_child
CMS_PAGE_customerservice_faq_child
CMS_PAGE_customerservice_faq_question_one
```