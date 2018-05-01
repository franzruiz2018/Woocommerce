Ubicar el archivo en: 

>misitio\wp-content\plugins\woocommerce\includes\wc-templates-functions.php

la funcion 

>woocommerce_content() 

reemplazar la linea 

```
<h1 class="page-title"><?php woocommerce_page_title(); ?></h1>
```

por 

```
<div class="section-title">
<h1 class="page-title"><?php woocommerce_page_title(); ?></h1>
<hr>
</div>
```
