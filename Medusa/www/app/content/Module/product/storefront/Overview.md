---
description: "Products are items or services that businesses sell to their customers. Learn about the available features and guides."
---

import DocCardList from '@theme/DocCardList';
import Icons from '@theme/Icon';

# Products

Products are items or services that businesses sell to their customers. This overview introduces the available features related to products.

:::note

Not a developer? Check out the [Products user guide](../../user-guide/products/manage.mdx).

:::

## Features

### Products Management

Admins can manage unlimited amount of products and their variants. They can manage the product’s details including their pricing, inventory, and more.

<DocCardList colSize={4} items={[
  {
    type: 'link',
    href: '/modules/products/admin/manage-products',
    label: 'Admin: Manage Products',
    customProps: {
      icon: Icons['academic-cap-solid'],
      description: 'Learn how to manage products using Admin APIs.',
    }
  },
  {
    type: 'link',
    href: '/user-guide/products/manage',
    label: 'User Guide: Products',
    customProps: {
      icon: Icons['users-solid'],
      description: 'Manage products in Medusa Admin.'
    }
  },
  {
    type: 'link',
    href: '/modules/products/storefront/show-products',
    label: 'Storefront: Show Products',
    customProps: {
      icon: Icons['academic-cap-solid'],
      description: 'Learn how to show products in a storefront.',
    }
  },
]} />

### Product Organization

Admins can organize products into categories, collections, tags, types, and more.

Customers can use this organization to filter products while browsing them.

<DocCardList colSize={4} items={[
  {
    type: 'link',
    href: '/modules/products/admin/manage-categories',
    label: 'Admin: Manage Categories',
    customProps: {
      icon: Icons['academic-cap-solid'],
      description: 'Learn how to manage categories using Admin APIs.',
    }
  },
  {
    type: 'link',
    href: '/user-guide/products/categories',
    label: 'User Guide: Categories',
    customProps: {
      icon: Icons['users-solid'],
      description: 'Learn how to manage categories in the Medusa Admin.'
    }
  },
  {
    type: 'link',
    href: '/modules/products/storefront/use-categories',
    label: 'Storefront: Use Categories',
    customProps: {
      icon: Icons['server-solid'],
      description: 'Learn how to use categories in a storefront.',
    }
  },
]} />

### Product Import and Export

Admins can bulk import and export products using CSV files. This facilitates moving data from other ecommerce platforms to Medusa.

<DocCardList colSize={4} items={[
  {
    type: 'link',
    href: '/modules/products/admin/import-products',
    label: 'Admin: Import Products',
    customProps: {
      icon: Icons['academic-cap-solid'],
      description: 'Learn how to import products into Medusa using Admin APIs.'
    }
  },
  {
    type: 'link',
    href: '/user-guide/products/import',
    label: 'User Guide: Import',
    customProps: {
      icon: Icons['users-solid'],
      description: 'Learn how to import products into Medusa Admin.'
    }
  },
  {
    type: 'link',
    href: '/user-guide/products/export',
    label: 'User Guide: Export',
    customProps: {
      icon: Icons['users-solid'],
      description: 'Learn how to export products from Medusa Admin.'
    }
  },
]} />

---

## Understand the Architecture

Learn how product-related entities are build, their relation to other modules, and more.

<DocCardList colSize={6} items={[
  {
    type: 'link',
    href: '/modules/products',
    label: 'Architecture: Product',
    customProps: {
      icon: Icons['circle-stack-solid'],
      description: 'Learn about the Product Architecture.',
    }
  },
  {
    type: 'link',
    href: '/modules/products/categories',
    label: 'Architecture: Category',
    customProps: {
      icon: Icons['circle-stack-solid'],
      description: 'Learn about the Product Category Architecture.',
    }
  },
]} />

---

## Related Modules

Discover Products’ relation to other modules in Medusa

<DocCardList colSize={4} items={[
  {
    type: 'link',
    href: '/modules/sales-channels/overview',
    label: 'Sales Channels',
    customProps: {
      icon: Icons['channels-solid'],
      description: 'Products availability can be specific to sales channels.',
    }
  },
  {
    type: 'link',
    href: '/modules/price-lists/overview',
    label: 'Price Lists',
    customProps: {
      icon: Icons['currency-dollar'],
      description: 'Override prices of products based on specific conditions.',
    }
  },
  {
    type: 'link',
    href: '/modules/discounts/overview',
    label: 'Discounts',
    customProps: {
      icon: Icons['receipt-percent'],
      description: 'Discounts can be created for specific products or collections.',
    }
  },
]} />

<DocCardList colSize={4} items={[
  {
    type: 'link',
    href: '/modules/gift-cards/overview',
    label: 'Gift Cards',
    customProps: {
      icon: Icons['gift-solid'],
      description: 'Gift cards can be sold as Products.',
    }
  },
  {
    type: 'link',
    href: '/modules/carts-and-checkout/overview',
    label: 'Carts and Checkout',
    customProps: {
      icon: Icons['shopping-cart-solid'],
      description: 'Allow customers to purchase your products.'
    }
  },
  {
    type: 'link',
    href: '/modules/orders/overview',
    label: 'Orders',
    customProps: {
      icon: Icons['check-circle-solid'],
      description: 'Product purchases can be managed as orders.'
    }
  },
]} />
