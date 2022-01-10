# Shopify: Recormendations by metafield
## Admin
 * Add metafield in Admin under Product Category `Product Recommendation Tag` it will generate the namespace and key as `my_fields.product_recommendation_tag`. 
   Click "select content type", select Text and leave as default. Save.

## Theme
 * Copy Liquid Template "product-recommendations-metafield.liquid" in Sections
 * Copy Liquid Template "product-card-cart.liquid" in Snippets
 * Add `{% section 'product-recommendations-metafield' %}` to product.liquid in Templates (see example file)

## Products
For example, we will use a Main product and available accessories for that product:

 * Go into each Main Product and set the metafield
 * Now add that value to each accessory product this will make it show on the Main Product
