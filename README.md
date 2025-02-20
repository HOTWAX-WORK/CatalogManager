# CatalogManager

Created a product Catalog named Practice
![Screenshot from 2025-02-20 11-23-36](https://github.com/user-attachments/assets/482b7735-0932-437c-93be-097c78544c40)
Assigned the particular catalog with store 9000 which was already created
![Screenshot from 2025-02-20 11-24-44](https://github.com/user-attachments/assets/ffac8c1e-953e-4256-bdf7-634d59e4b075)

Created product Catagory

<?xml version="1.0" encoding="UTF-8"?>
<entity-engine-xml>
    <ProductCategory productCategoryId="PROMOTION" productCategoryTypeId="CATALOG_CATEGORY" categoryName="PROMOTION" />
    <ProductCategory productCategoryId="BROWSE_ROOT" productCategoryTypeId="CATALOG_CATEGORY" categoryName="BROWSE_ROOT" />
    <ProductCategory productCategoryId="CHILDREN" productCategoryTypeId="CATALOG_CATEGORY" primaryParentCategoryId="BROWSE_ROOT" categoryName="CHILDREN"/>
</entity-engine-xml>


Assigned the Practice Catalog with the PROMOTION CATEGORY that consists products in pomotion
![Screenshot from 2025-02-20 11-26-05](https://github.com/user-attachments/assets/8bb33655-cd25-48b6-a575-c70a6cf9436d)


Catalog on the localhost ecommerce component
![Screenshot from 2025-02-20 11-27-40](https://github.com/user-attachments/assets/771b06eb-2b62-4846-a3b8-03cb1c9555c1)

Added Product with corresponding categories

<?xml version="1.0" encoding="UTF-8"?>
<entity-engine-xml>
    <Product productId="C2" productTypeId="DIGITAL_GOOD" primaryProductCategoryId="CHILDREN" isVirtual="Y"/>
    <Product productId="C1" productTypeId="DIGITAL_GOOD" primaryProductCategoryId="CHILDREN" isVirtual="Y"/>
    <Product productId="C1_WHITE_2" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_WHITE_3" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_WHITE_4" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_WHITE_5" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_BROWN_2" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_BROWN_3" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_BROWN_4" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C1_BROWN_5" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C2_RED_2" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C2_RED_3" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C2_RED_5" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C2_BLACK_2" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C2_BLACK_3" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
    <Product productId="C2_BLACK_5" productTypeId="FINISHED_GOOD" primaryProductCategoryId="CHILDREN" isVariant="Y"/>
</entity-engine-xml>

Created Product association

<?xml version="1.0" encoding="UTF-8"?>
<entity-engine-xml>
    <ProductAssoc productId="C1" productIdTo="C1_WHITE_2" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_WHITE_3" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_WHITE_4" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_WHITE_5" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_BROWN_2" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_BROWN_3" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_BROWN_4" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C1" productIdTo="C1_BROWN_5" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C2" productIdTo="C2_RED_2" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C2" productIdTo="C2_RED_3" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C2" productIdTo="C2_RED_5" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C2" productIdTo="C2_BLACK_2" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C2" productIdTo="C2_BLACK_3" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
    <ProductAssoc productId="C2" productIdTo="C2_BLACK_5" productAssocTypeId="PRODUCT_VARIANT" fromDate="2025-02-02 00:00:00.0"/>
</entity-engine-xml>

Added Product Features 
<?xml version="1.0" encoding="UTF-8"?>
<entity-engine-xml>
    <ProductFeature productFeatureId="SIZE_5" productFeatureTypeId="SIZE" productFeatureCategoryId="TEXT" description="5" />
    <ProductFeature productFeatureId="SIZE_4" productFeatureTypeId="SIZE" productFeatureCategoryId="TEXT" description="4" />
    <ProductFeature productFeatureId="SIZE_3" productFeatureTypeId="SIZE" productFeatureCategoryId="TEXT" description="3" />
    <ProductFeature productFeatureId="SIZE_2" productFeatureTypeId="SIZE" productFeatureCategoryId="TEXT" description="2" />
    <ProductFeature productFeatureId="BROWN" productFeatureTypeId="COLOR" productFeatureCategoryId="TEXT" description="BROWN" />
    <ProductFeature productFeatureId="WHITE" productFeatureTypeId="COLOR" productFeatureCategoryId="TEXT" description="WHITE" />
    <ProductFeature productFeatureId="BLACK" productFeatureTypeId="COLOR" productFeatureCategoryId="TEXT" description="BLACK" />
    <ProductFeature productFeatureId="RED" productFeatureTypeId="COLOR" productFeatureCategoryId="TEXT" description="RED" />
</entity-engine-xml>

Displaying Product on the screen of PROMOTION CATEGORY

![Screenshot from 2025-02-20 11-27-55](https://github.com/user-attachments/assets/39712a60-19f7-49c0-9d35-3d1fa7b1279e)

A particular pdouct C1 Details
![Screenshot from 2025-02-20 11-28-22](https://github.com/user-attachments/assets/4927b65e-5d57-4aef-a15c-28fbe7ec4b45)
To add a product to cart we need particular product price so created price for the relevant order features 
![Screenshot from 2025-02-20 11-31-00](https://github.com/user-attachments/assets/ed74f0ab-e2ee-4294-9b29-278f680edff5)
Product Added to cart
![Screenshot from 2025-02-20 11-31-41](https://github.com/user-attachments/assets/ca68ac26-e7b3-41eb-92d5-eebd26546130)
Order Confirmation Screenshots
![Screenshot from 2025-02-20 14-11-11](https://github.com/user-attachments/assets/16ae5686-fca9-4642-9302-b711df87375e)

![Screenshot from 2025-02-20 14-11-21](https://github.com/user-attachments/assets/3542fe8f-b2a3-4ab9-b093-5610689a8306)

![Screenshot from 2025-02-20 14-11-26](https://github.com/user-attachments/assets/12be35d9-c58f-468b-b9cd-ff0c20054f9e)
