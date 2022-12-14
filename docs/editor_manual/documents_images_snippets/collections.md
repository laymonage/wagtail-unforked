# Collections

Access to specific sets of images and documents can be controlled by setting up ‘collections’. By default all images and documents belong to the ‘root’ collection, but users with appropriate permissions can create new collections through the **Settings -> Collections** area of the admin interface.

![Collections listing with three rows: Bakeries, BreadPage Images, Other](../../_static/images/collections_list.png)

## Add a collection

-   Clicking the **add a collection** button will allow you to create a collection. Name your collection and click **save** .

![Form to create a collection, with a Name text field and Parent dropdown field](../../_static/images/collections_create_collection.png)

## Add images / documents to a collection

-   Navigate to the **Images** or **Documents** section and select a collection from the dropdown menu.
-   You can also select a collection as part of uploading multiple images or documents.

![Screenshot of the Add Images page, with a drag-and-drop zone, with the Collection dropdown field highlighted in red](../../_static/images/collections_create_collection_upload_images.png)

-   You can also edit an image or document directly by clicking on it to assign it to a collection.

![Screenshot of the image editing form for an image titled Olivia Ava, with the Collection field highlighted in red](../../_static/images/collections_edit_img_view.png)

(collection_privacy_settings)=

## Privacy settings

-   To set permissions determining who is able to view documents within a collection, navigate to **Settings > Collections** and select a collection. Then click the privacy button above the collection name.

![The collection editing form for BreadPage Images, with a red highlight around the Privacy: "public" form control](../../_static/images/collections_privacy_button.png)

-   Within the privacy settings overlay, select the level of privacy for the collection.

![Change privacy modal dialog, with four options as radio buttons](../../_static/images/collections_privacy_overlay.png)

Permissions set on a collection apply to that collection and all collections below it in the hierarchy. Therefore, if you make the 'root' collection private, all documents in the site will be private. Permissions set on other collections apply to that collection only.

```{Note}
Although privacy settings are added to a collection, they are only enforced for documents within the collection. Privacy settings do not apply to images.
```
