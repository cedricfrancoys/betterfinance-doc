### Highlight
Data Model:
* picture
* title
* description
* URL


### Members
Data Model:
* name
* country_code
* description
* contact_info
* url
* logo

## Articles

### Articles types
	News ("latest news")
	Newsletter
	Press coverage ("in the media")
		
## Publications
	
	
### Publications types
	Positions papers & Consultations
	Research papers
	Press releases
	Public letters
	Presentations

## Categories (non-hierarchical)

	Annual reports
	Key Priorities
	Research Reports
	Open letters
	Events
	Insurance
	Life insurance
	Pensions
	Banking
	Financial Market Infrastructure
	Financial Education
	FinTech
	Audit
	Corporate Governance
	Investment
	Consumer Affairs
	Capital Markets (equity & bonds)
	Shareholder Rights
	Packaged Investment Products
	
	
	## Custom types 
Under WordPress there are only 2 core types related to content organisation: post and taxonomy.

For that reason, WP litterature often refers to "Custom Posts" whereas it is actually talking about custom types.

* Custom Post Type UI from WebDevStudios

This plugin allows to define unlimited custom posts and custom taxonomies.
It also allows to select which meta boxes (see below) are supported for each type.

So far, these are nothing more than aliases for posts and taxonomies.

### Custom fields

It is not possible to define a structure per-se for each type (as it is possible in most CMS).
However, it is possible to attach meta data to each post.

It is then possible to attach custom lists of meta data to each post type.
WP core uses this for some fields, and back-end litterature refers to it as "Meta Boxes".
The idea is to define meta data and specify its "type" (the kind of data it will hold and how to display the related edition widget).

Two plugins allow to generalise this approach:

* CMB2 (no UI)
* CMB2 admin extension (offers a basic UI)

Custom fields defined with this plugin are pre-pended with an underscore ("_") and result in a slug from the field name (replacing spaces with underscores).


### Custom taxonomies


Plugin for enhance admin filtering: Admin Taxonomy Filter

## Custom views

To display custom posts in a customized manner (there is no point in defining custom fields if we cannot display them) we need another plugin:

* Content Views Pro, from CVSOFT

This plugin allows to defines unlimited views for each Post type.
It also provides search, filtering and pagination capabilities.
+ PHP hooks are available (`pt_cv_view_type_custom_output`, `pt_cv_field_content_excerpt`) allowing to have fully customized templates for lists.


## Integration custom types inside the website map

Custom Post Type Permalink Settings

--> Simple Post Type Permalinks


## Templating

### Pages
Under WP, pages are a special type of posts.

WP bakery

Allows to define clear division of pages in responsive rows and columns.

### Custom types
Inside the current theme main directory (e.g. \wp-content\themes\twentysixteen), copy single.php and rename it to single-{cutsom_type}.php
Inside the template-parts subdir, create a related {custom_type}.php file.

Edit single-{cutsom_type}.php and update its call to `get_template_part` to target the newly created template part.

Customize `template-parts\{custom_type}.php` according to the design.

## Rights and Roles

* Adminize
* User Role Editor

## Admin

Complementary option, use Dashicons + Custom Post Types
to choose the icons in the WP admin menu for the custom types