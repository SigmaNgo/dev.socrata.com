---
layout: with-sidebar
sidebar: documentation
title: Data Transform Listing
---

These are the transformation functions available in the data source ingress API.
These functions can be used to transform and validate your data before you publish
your dataset for consumption.

These functions apply in the "Data Transforms" editor in the ingress UI.

See the [Apiary Page](http://socratapublishing.docs.apiary.io/) for the data source ingress
API for how to use the transform functions as an API user.



| Function Name | Description |
| ---- | ---- |
| [`+`](/docs/transforms/add.html) | Add two numbers together |
| [`||`](/docs/transforms/concatenate.html) | concatenate two strings |
| [`/`](/docs/transforms/divide.html) | Divide a number by another |
| [`==`](/docs/transforms/equal.html) | Return true if the left side equals the right |
| [`=`](/docs/transforms/equal.html) | Return true if the left side equals the right |
| [`^`](/docs/transforms/exponent.html) | No documentation is available. |
| [`>`](/docs/transforms/greater_than.html) | Return true if the value on the left is greater than the value on the right |
| [`>=`](/docs/transforms/greater_than_equal.html) | Return true if the value on the left is greater than or equal to the value on the right |
| [`<`](/docs/transforms/less_than.html) | Return true if the value on the left is less than the value on the right |
| [`<=`](/docs/transforms/less_than_equal.html) | Return true if the value on the left is less than or equal to the value on the right |
| [`%`](/docs/transforms/modulo.html) | Find the remainder(modulus) of one number divided by another |
| [`*`](/docs/transforms/multiply.html) | Multiply two numbers together |
| [`!=`](/docs/transforms/not_equal.html) | Return true if the left side does not equal the right |
| [`<>`](/docs/transforms/not_equal.html) | Return true if the left side does not equal the right |
| [`-`](/docs/transforms/subtract.html) | Subtract a number from another |
| [`and`](/docs/transforms/and.html) | Logical and of two boolean values |
| [`between`](/docs/transforms/between.html) | Return true if the left is within the range of the right values |
| [`case`](/docs/transforms/case.html) | Evaluate a series of true/false expressions (predicates) and return the next consequent. |
| [`coalesce`](/docs/transforms/coalesce.html) | Take the leftmost non-null value. |
| [`contains`](/docs/transforms/contains.html) | tell whether or not a string contains another string |
| [`ensure_within`](/docs/transforms/ensure_within.html) | ensure_within is a function which takes a point and a multipolygon |
| [`error`](/docs/transforms/error.html) | Make an error. This is useful in conjunction with a case function, |
| [`forgive`](/docs/transforms/forgive.html) | Turn an error into a null value. This is useful if you have a transformation |
| [`geocode`](/docs/transforms/geocode.html) | geocode is a function which takes human readable addresses |
| [`geocode_esri`](/docs/transforms/geocode_esri.html) | geocode_esri is a function which takes human readable addresses |
| [`http_get`](/docs/transforms/http_get.html) | Make an HTTP Get request to a URL. The response is returned. If the server |
| [`in`](/docs/transforms/in.html) | Whether or not a value is in a set of other values |
| [`is_not_null`](/docs/transforms/is_not_null.html) | Whether or not a value is not null |
| [`is_null`](/docs/transforms/is_null.html) | Whether or not a value is null |
| [`is_within`](/docs/transforms/is_within.html) | is_within is a function which takes a point and a multipolygon |
| [`json_pluck`](/docs/transforms/json_pluck.html) | Pluck a value out of a JSON string. The returned value may be a primitive like a |
| [`like`](/docs/transforms/like.html) | If a string is like another string. |
| [`location_to_point`](/docs/transforms/location_to_point.html) | Turn a location value into a point |
| [`lower`](/docs/transforms/lower.html) | lowercase a string |
| [`make_location`](/docs/transforms/make_location.html) | make_location makes a location column from human readable |
| [`make_point`](/docs/transforms/make_point.html) | function to make a point out of a Y (latitude) and X (longitude) coordinate. |
| [`not`](/docs/transforms/not.html) | Invert a boolean |
| [`not_between`](/docs/transforms/not_between.html) | Return true if the left is not within the range of the right values |
| [`not_in`](/docs/transforms/not_in.html) | Whether or not a value is absent from a set of other values |
| [`not_like`](/docs/transforms/not_like.html) | If a string is not like another string. |
| [`or`](/docs/transforms/or.html) | Logical or of two boolean values |
| [`regex_capture`](/docs/transforms/regex_capture.html) | function to capture a piece of text based on a regular expression |
| [`regex_named_capture`](/docs/transforms/regex_named_capture.html) | capture a piece of text based on a regular expression |
| [`regex_replace`](/docs/transforms/regex_replace.html) | function to replace a piece of text based on a regular expression |
| [`replace`](/docs/transforms/replace.html) | replace text with another piece of text |
| [`replace_first`](/docs/transforms/replace_first.html) | replace the first occurrence of a piece of text with another piece of text |
| [`reproject`](/docs/transforms/reproject.html) | reproject a geometry from one projection to another. |
| [`reproject_to_wgs84`](/docs/transforms/reproject_to_wgs84.html) | function to reproject a geometry to WGS84. This will allow the geometry |
| [`set_projection`](/docs/transforms/set_projection.html) | function to explicitly set the projection value on geometries which do not have projection |
| [`split_select`](/docs/transforms/split_select.html) | function to split a piece of text on a token, and then select |
| [`starts_with`](/docs/transforms/starts_with.html) | tell whether or a not a string is prefixed with another string |
| [`state_boundary`](/docs/transforms/state_boundary.html) | returns the boundary of the US state |
| [`to_boolean`](/docs/transforms/to_boolean.html) | cast a value to a true or false |
| [`to_checkbox`](/docs/transforms/to_checkbox.html) | No documentation is available. |
| [`to_fixed_timestamp`](/docs/transforms/to_fixed_timestamp.html) | Turn a text value into a datetime with a fixed timezone. |
| [`to_floating_timestamp`](/docs/transforms/to_floating_timestamp.html) | Turn a text value into a floating datetime. "Floating" means the timezone |
| [`to_line`](/docs/transforms/to_line.html) | parse a WKT (text) representation of a line into a line value |
| [`to_location`](/docs/transforms/to_location.html) | Attempt to parse an address into a location column. |
| [`to_multiline`](/docs/transforms/to_multiline.html) | parse a WKT (text) representation of a multiline into a multiline value |
| [`to_multipoint`](/docs/transforms/to_multipoint.html) | parse a WKT (text) representation of a multipoint into a multipoint value |
| [`to_multipolygon`](/docs/transforms/to_multipolygon.html) | parse a WKT (text) representation of a multiline into a multiline value |
| [`to_number`](/docs/transforms/to_number.html) | cast a value to a number |
| [`to_point`](/docs/transforms/to_point.html) | parse a WKT (text) representation of a point into a point value |
| [`to_polygon`](/docs/transforms/to_polygon.html) | parse a WKT (text) representation of a polygon into a polygon value |
| [`to_text`](/docs/transforms/to_text.html) | cast a value to text |
| [`upper`](/docs/transforms/upper.html) | uppercase a string |
| [`xml_pluck`](/docs/transforms/xml_pluck.html) | Pluck a value out of an XML string using XPath. The returned value will be a string. |