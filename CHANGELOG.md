## 0.7.4
Callbacks are now called **after** the operation has been styled, instead of before.

## 0.7.3
Hopefully improved whitespace handling inside `ListElements`, and improved the logic behind `LineBreak` operations.

## 0.7.2
Fixes for table cells with no width, also always ensure a `Format` object is attached to an Operation.

## 0.7.1
Added support for tables with percentage widths.

## 0.6.13
Added support for text-align CSS classes inside tables

## 0.6.12
Added support for <br> tags.

## 0.6.11
Fixed an issue where inserting an image as the only content of a TableCell would cause it to be inserted in the wrong place.