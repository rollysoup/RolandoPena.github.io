[Video_Games_Sales_Analysis.html](https://github.com/user-attachments/files/28921981/Video_Games_Sales_Analysis.html)
<!DOCTYPE html>

<html lang="en">
<head><meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>F2</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .pm { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation.Marker */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0 solid transparent;
  border-right: 0 solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0 solid transparent;
  border-bottom: 0 solid transparent;
}

/*
 * Lumino
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
}

.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.lm-AccordionPanel[data-orientation='horizontal'] > .lm-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-CommandPalette-search {
  flex: 0 0 auto;
}

.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}

.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}

.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}

.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
  border: 1px solid transparent;
  background-color: transparent;
  position: absolute;
  z-index: 1;
  right: 3%;
  top: 0;
  bottom: 0;
  margin: auto;
  padding: 7px 0;
  display: none;
  vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
  content: 'X';
  display: block;
  width: 15px;
  height: 15px;
  text-align: center;
  color: #000;
  font-weight: normal;
  font-size: 12px;
  cursor: pointer;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-DockPanel {
  z-index: 0;
}

.lm-DockPanel-widget {
  z-index: 0;
}

.lm-DockPanel-tabBar {
  z-index: 1;
}

.lm-DockPanel-handle {
  z-index: 2;
}

.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}

.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}

.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}

.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}

.lm-Menu-item {
  display: table-row;
}

.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}

.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}

.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}

.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}

.lm-MenuBar-item {
  box-sizing: border-box;
}

.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}

.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}

.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}

.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}

.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-SplitPanel-child {
  z-index: 0;
}

.lm-SplitPanel-handle {
  z-index: 1;
}

.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}

.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}

.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}

.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}

.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}

.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
  touch-action: none; /* Disable native Drag/Drop */
}

.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}

.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}

.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
}

.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}

.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}

.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
  background: inherit;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabPanel-tabBar {
  z-index: 1;
}

.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

.jp-Collapse-header {
  padding: 1px 12px;
  background-color: var(--jp-layout-color1);
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  align-items: center;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  text-transform: uppercase;
  user-select: none;
}

.jp-Collapser-icon {
  height: 16px;
}

.jp-Collapse-header-collapsed .jp-Collapser-icon {
  transform: rotate(-90deg);
  margin: auto 0;
}

.jp-Collapser-title {
  line-height: 25px;
}

.jp-Collapse-contents {
  padding: 0 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add-above: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5MikiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik00Ljc1IDQuOTMwNjZINi42MjVWNi44MDU2NkM2LjYyNSA3LjAxMTkxIDYuNzkzNzUgNy4xODA2NiA3IDcuMTgwNjZDNy4yMDYyNSA3LjE4MDY2IDcuMzc1IDcuMDExOTEgNy4zNzUgNi44MDU2NlY0LjkzMDY2SDkuMjVDOS40NTYyNSA0LjkzMDY2IDkuNjI1IDQuNzYxOTEgOS42MjUgNC41NTU2NkM5LjYyNSA0LjM0OTQxIDkuNDU2MjUgNC4xODA2NiA5LjI1IDQuMTgwNjZINy4zNzVWMi4zMDU2NkM3LjM3NSAyLjA5OTQxIDcuMjA2MjUgMS45MzA2NiA3IDEuOTMwNjZDNi43OTM3NSAxLjkzMDY2IDYuNjI1IDIuMDk5NDEgNi42MjUgMi4zMDU2NlY0LjE4MDY2SDQuNzVDNC41NDM3NSA0LjE4MDY2IDQuMzc1IDQuMzQ5NDEgNC4zNzUgNC41NTU2NkM0LjM3NSA0Ljc2MTkxIDQuNTQzNzUgNC45MzA2NiA0Ljc1IDQuOTMwNjZaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC43Ii8+CjwvZz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTExLjUgOS41VjExLjVMMi41IDExLjVWOS41TDExLjUgOS41Wk0xMiA4QzEyLjU1MjMgOCAxMyA4LjQ0NzcyIDEzIDlWMTJDMTMgMTIuNTUyMyAxMi41NTIzIDEzIDEyIDEzTDIgMTNDMS40NDc3MiAxMyAxIDEyLjU1MjMgMSAxMlY5QzEgOC40NDc3MiAxLjQ0NzcxIDggMiA4TDEyIDhaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5MiI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KC0xIDAgMCAxIDEwIDEuNTU1NjYpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==);
  --jp-icon-add-below: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5OCkiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik05LjI1IDEwLjA2OTNMNy4zNzUgMTAuMDY5M0w3LjM3NSA4LjE5NDM0QzcuMzc1IDcuOTg4MDkgNy4yMDYyNSA3LjgxOTM0IDcgNy44MTkzNEM2Ljc5Mzc1IDcuODE5MzQgNi42MjUgNy45ODgwOSA2LjYyNSA4LjE5NDM0TDYuNjI1IDEwLjA2OTNMNC43NSAxMC4wNjkzQzQuNTQzNzUgMTAuMDY5MyA0LjM3NSAxMC4yMzgxIDQuMzc1IDEwLjQ0NDNDNC4zNzUgMTAuNjUwNiA0LjU0Mzc1IDEwLjgxOTMgNC43NSAxMC44MTkzTDYuNjI1IDEwLjgxOTNMNi42MjUgMTIuNjk0M0M2LjYyNSAxMi45MDA2IDYuNzkzNzUgMTMuMDY5MyA3IDEzLjA2OTNDNy4yMDYyNSAxMy4wNjkzIDcuMzc1IDEyLjkwMDYgNy4zNzUgMTIuNjk0M0w3LjM3NSAxMC44MTkzTDkuMjUgMTAuODE5M0M5LjQ1NjI1IDEwLjgxOTMgOS42MjUgMTAuNjUwNiA5LjYyNSAxMC40NDQzQzkuNjI1IDEwLjIzODEgOS40NTYyNSAxMC4wNjkzIDkuMjUgMTAuMDY5M1oiIGZpbGw9IiM2MTYxNjEiIHN0cm9rZT0iIzYxNjE2MSIgc3Ryb2tlLXdpZHRoPSIwLjciLz4KPC9nPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMi41IDUuNUwyLjUgMy41TDExLjUgMy41TDExLjUgNS41TDIuNSA1LjVaTTIgN0MxLjQ0NzcyIDcgMSA2LjU1MjI4IDEgNkwxIDNDMSAyLjQ0NzcyIDEuNDQ3NzIgMiAyIDJMMTIgMkMxMi41NTIzIDIgMTMgMi40NDc3MiAxMyAzTDEzIDZDMTMgNi41NTIyOSAxMi41NTIzIDcgMTIgN0wyIDdaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5OCI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KDEgMS43NDg0NmUtMDcgMS43NDg0NmUtMDcgLTEgNCAxMy40NDQzKSIvPgo8L2NsaXBQYXRoPgo8L2RlZnM+Cjwvc3ZnPgo=);
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bell: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE2IDE2IiB2ZXJzaW9uPSIxLjEiPgogICA8cGF0aCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzMzMzMzIgogICAgICBkPSJtOCAwLjI5Yy0xLjQgMC0yLjcgMC43My0zLjYgMS44LTEuMiAxLjUtMS40IDMuNC0xLjUgNS4yLTAuMTggMi4yLTAuNDQgNC0yLjMgNS4zbDAuMjggMS4zaDVjMC4wMjYgMC42NiAwLjMyIDEuMSAwLjcxIDEuNSAwLjg0IDAuNjEgMiAwLjYxIDIuOCAwIDAuNTItMC40IDAuNi0xIDAuNzEtMS41aDVsMC4yOC0xLjNjLTEuOS0wLjk3LTIuMi0zLjMtMi4zLTUuMy0wLjEzLTEuOC0wLjI2LTMuNy0xLjUtNS4yLTAuODUtMS0yLjItMS44LTMuNi0xLjh6bTAgMS40YzAuODggMCAxLjkgMC41NSAyLjUgMS4zIDAuODggMS4xIDEuMSAyLjcgMS4yIDQuNCAwLjEzIDEuNyAwLjIzIDMuNiAxLjMgNS4yaC0xMGMxLjEtMS42IDEuMi0zLjQgMS4zLTUuMiAwLjEzLTEuNyAwLjMtMy4zIDEuMi00LjQgMC41OS0wLjcyIDEuNi0xLjMgMi41LTEuM3ptLTAuNzQgMTJoMS41Yy0wLjAwMTUgMC4yOCAwLjAxNSAwLjc5LTAuNzQgMC43OS0wLjczIDAuMDAxNi0wLjcyLTAuNTMtMC43NC0wLjc5eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-bug-dot: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiPgogICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTcuMTkgOEgyMFYxMEgxNy45MUMxNy45NiAxMC4zMyAxOCAxMC42NiAxOCAxMVYxMkgyMFYxNEgxOC41SDE4VjE0LjAyNzVDMTUuNzUgMTQuMjc2MiAxNCAxNi4xODM3IDE0IDE4LjVDMTQgMTkuMjA4IDE0LjE2MzUgMTkuODc3OSAxNC40NTQ5IDIwLjQ3MzlDMTMuNzA2MyAyMC44MTE3IDEyLjg3NTcgMjEgMTIgMjFDOS43OCAyMSA3Ljg1IDE5Ljc5IDYuODEgMThINFYxNkg2LjA5QzYuMDQgMTUuNjcgNiAxNS4zNCA2IDE1VjE0SDRWMTJINlYxMUM2IDEwLjY2IDYuMDQgMTAuMzMgNi4wOSAxMEg0VjhINi44MUM3LjI2IDcuMjIgNy44OCA2LjU1IDguNjIgNi4wNEw3IDQuNDFMOC40MSAzTDEwLjU5IDUuMTdDMTEuMDQgNS4wNiAxMS41MSA1IDEyIDVDMTIuNDkgNSAxMi45NiA1LjA2IDEzLjQyIDUuMTdMMTUuNTkgM0wxNyA0LjQxTDE1LjM3IDYuMDRDMTYuMTIgNi41NSAxNi43NCA3LjIyIDE3LjE5IDhaTTEwIDE2SDE0VjE0SDEwVjE2Wk0xMCAxMkgxNFYxMEgxMFYxMloiIGZpbGw9IiM2MTYxNjEiLz4KICAgICAgICA8cGF0aCBkPSJNMjIgMTguNUMyMiAyMC40MzMgMjAuNDMzIDIyIDE4LjUgMjJDMTYuNTY3IDIyIDE1IDIwLjQzMyAxNSAxOC41QzE1IDE2LjU2NyAxNi41NjcgMTUgMTguNSAxNUMyMC40MzMgMTUgMjIgMTYuNTY3IDIyIDE4LjVaIiBmaWxsPSIjNjE2MTYxIi8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBzaGFwZS1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiI+CiAgICA8cGF0aCBkPSJNNi41OSwzLjQxTDIsOEw2LjU5LDEyLjZMOCwxMS4xOEw0LjgyLDhMOCw0LjgyTDYuNTksMy40MU0xMi40MSwzLjQxTDExLDQuODJMMTQuMTgsOEwxMSwxMS4xOEwxMi40MSwxMi42TDE3LDhMMTIuNDEsMy40MU0yMS41OSwxMS41OUwxMy41LDE5LjY4TDkuODMsMTZMOC40MiwxNy40MUwxMy41LDIyLjVMMjMsMTNMMjEuNTksMTEuNTlaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-collapse-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNNiAxM3YyaDh2LTJ6IiAvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1jb25zb2xlLWljb24tYmFja2dyb3VuZC1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtY29uc29sZS1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIj4KICAgIDxwYXRoIGQ9Ik0xMDUgMTI3LjNoNDB2MTIuOGgtNDB6TTUxLjEgNzdMNzQgOTkuOWwtMjMuMyAyMy4zIDEwLjUgMTAuNSAyMy4zLTIzLjNMOTUgOTkuOSA4NC41IDg5LjQgNjEuNiA2Ni41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-delete: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2cHgiIGhlaWdodD0iMTZweCI+CiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIiAvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjI2MjYyIiBkPSJNNiAxOWMwIDEuMS45IDIgMiAyaDhjMS4xIDAgMi0uOSAyLTJWN0g2djEyek0xOSA0aC0zLjVsLTEtMWgtNWwtMSAxSDV2MmgxNFY0eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-duplicate: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTIuNzk5OTggMC44NzVIOC44OTU4MkM5LjIwMDYxIDAuODc1IDkuNDQ5OTggMS4xMzkxNCA5LjQ0OTk4IDEuNDYxOThDOS40NDk5OCAxLjc4NDgyIDkuMjAwNjEgMi4wNDg5NiA4Ljg5NTgyIDIuMDQ4OTZIMy4zNTQxNUMzLjA0OTM2IDIuMDQ4OTYgMi43OTk5OCAyLjMxMzEgMi43OTk5OCAyLjYzNTk0VjkuNjc5NjlDMi43OTk5OCAxMC4wMDI1IDIuNTUwNjEgMTAuMjY2NyAyLjI0NTgyIDEwLjI2NjdDMS45NDEwMyAxMC4yNjY3IDEuNjkxNjUgMTAuMDAyNSAxLjY5MTY1IDkuNjc5NjlWMi4wNDg5NkMxLjY5MTY1IDEuNDAzMjggMi4xOTA0IDAuODc1IDIuNzk5OTggMC44NzVaTTUuMzY2NjUgMTEuOVY0LjU1SDExLjA4MzNWMTEuOUg1LjM2NjY1Wk00LjE0MTY1IDQuMTQxNjdDNC4xNDE2NSAzLjY5MDYzIDQuNTA3MjggMy4zMjUgNC45NTgzMiAzLjMyNUgxMS40OTE3QzExLjk0MjcgMy4zMjUgMTIuMzA4MyAzLjY5MDYzIDEyLjMwODMgNC4xNDE2N1YxMi4zMDgzQzEyLjMwODMgMTIuNzU5NCAxMS45NDI3IDEzLjEyNSAxMS40OTE3IDEzLjEyNUg0Ljk1ODMyQzQuNTA3MjggMTMuMTI1IDQuMTQxNjUgMTIuNzU5NCA0LjE0MTY1IDEyLjMwODNWNC4xNDE2N1oiIGZpbGw9IiM2MTYxNjEiLz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNOS40MzU3NCA4LjI2NTA3SDguMzY0MzFWOS4zMzY1QzguMzY0MzEgOS40NTQzNSA4LjI2Nzg4IDkuNTUwNzggOC4xNTAwMiA5LjU1MDc4QzguMDMyMTcgOS41NTA3OCA3LjkzNTc0IDkuNDU0MzUgNy45MzU3NCA5LjMzNjVWOC4yNjUwN0g2Ljg2NDMxQzYuNzQ2NDUgOC4yNjUwNyA2LjY1MDAyIDguMTY4NjQgNi42NTAwMiA4LjA1MDc4QzYuNjUwMDIgNy45MzI5MiA2Ljc0NjQ1IDcuODM2NSA2Ljg2NDMxIDcuODM2NUg3LjkzNTc0VjYuNzY1MDdDNy45MzU3NCA2LjY0NzIxIDguMDMyMTcgNi41NTA3OCA4LjE1MDAyIDYuNTUwNzhDOC4yNjc4OCA2LjU1MDc4IDguMzY0MzEgNi42NDcyMSA4LjM2NDMxIDYuNzY1MDdWNy44MzY1SDkuNDM1NzRDOS41NTM2IDcuODM2NSA5LjY1MDAyIDcuOTMyOTIgOS42NTAwMiA4LjA1MDc4QzkuNjUwMDIgOC4xNjg2NCA5LjU1MzYgOC4yNjUwNyA5LjQzNTc0IDguMjY1MDdaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC41Ii8+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-error: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjE5IiByPSIyIi8+PHBhdGggZD0iTTEwIDNoNHYxMmgtNHoiLz48L2c+CjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMjR2MjRIMHoiLz4KPC9zdmc+Cg==);
  --jp-icon-expand-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNMTEgMTBIOXYzSDZ2MmgzdjNoMnYtM2gzdi0yaC0zeiIgLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-dot: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWRvdCIgZmlsbD0iI0ZGRiI+CiAgICA8Y2lyY2xlIGN4PSIxOCIgY3k9IjE3IiByPSIzIj48L2NpcmNsZT4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-filter: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-folder-favorite: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBmaWxsPSJub25lIi8+PHBhdGggY2xhc3M9ImpwLWljb24zIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxNjE2MSIgZD0iTTIwIDZoLThsLTItMkg0Yy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjhjMC0xLjEtLjktMi0yLTJ6bS0yLjA2IDExTDE1IDE1LjI4IDEyLjA2IDE3bC43OC0zLjMzLTIuNTktMi4yNCAzLjQxLS4yOUwxNSA4bDEuMzQgMy4xNCAzLjQxLjI5LTIuNTkgMi4yNC43OCAzLjMzeiIvPgo8L3N2Zz4K);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-home: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xMCAyMHYtNmg0djZoNXYtOGgzTDEyIDMgMiAxMmgzdjh6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUwLjk3OCA1MC45NzgiPgoJPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KCQk8cGF0aCBkPSJNNDMuNTIsNy40NThDMzguNzExLDIuNjQ4LDMyLjMwNywwLDI1LjQ4OSwwQzE4LjY3LDAsMTIuMjY2LDIuNjQ4LDcuNDU4LDcuNDU4CgkJCWMtOS45NDMsOS45NDEtOS45NDMsMjYuMTE5LDAsMzYuMDYyYzQuODA5LDQuODA5LDExLjIxMiw3LjQ1NiwxOC4wMzEsNy40NThjMCwwLDAuMDAxLDAsMC4wMDIsMAoJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoKCQkJIE00Mi4xMDYsNDIuMTA1Yy00LjQzMiw0LjQzMS0xMC4zMzIsNi44NzItMTYuNjE1LDYuODcyaC0wLjAwMmMtNi4yODUtMC4wMDEtMTIuMTg3LTIuNDQxLTE2LjYxNy02Ljg3MgoJCQljLTkuMTYyLTkuMTYzLTkuMTYyLTI0LjA3MSwwLTMzLjIzM0MxMy4zMDMsNC40NCwxOS4yMDQsMiwyNS40ODksMmM2LjI4NCwwLDEyLjE4NiwyLjQ0LDE2LjYxNyw2Ljg3MgoJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4KCQk8cGF0aCBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1MwoJCQljMC40NjgtMC41MzYsMC45MjMtMS4wNjIsMS4zNjctMS41NzVjMC42MjYtMC43NTMsMS4xMDQtMS40NzgsMS40MzYtMi4xNzVjMC4zMzEtMC43MDcsMC40OTUtMS41NDEsMC40OTUtMi41CgkJCWMwLTEuMDk2LTAuMjYtMi4wODgtMC43NzktMi45NzljLTAuNTY1LTAuODc5LTEuNTAxLTEuMzM2LTIuODA2LTEuMzY5Yy0xLjgwMiwwLjA1Ny0yLjk4NSwwLjY2Ny0zLjU1LDEuODMyCgkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkKCQkJYzEuMDYyLTEuNjQsMi44NTUtMi40ODEsNS4zNzgtMi41MjdjMi4xNiwwLjAyMywzLjg3NCwwLjYwOCw1LjE0MSwxLjc1OGMxLjI3OCwxLjE2LDEuOTI5LDIuNzY0LDEuOTUsNC44MTEKCQkJYzAsMS4xNDItMC4xMzcsMi4xMTEtMC40MSwyLjkxMWMtMC4zMDksMC44NDUtMC43MzEsMS41OTMtMS4yNjgsMi4yNDNjLTAuNDkyLDAuNjUtMS4wNjgsMS4zMTgtMS43MywyLjAwMgoJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5CgkJCUMyNi41ODksMzIuMjE4LDIzLjU3OCwzMi4yMTgsMjMuNTc4LDMyLjIxOHogTTIzLjU3OCwzOC4yMnYtMy40ODRoMy4wNzZ2My40ODRIMjMuNTc4eiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaW5zcGVjdG9yLWljb24tY29sb3IganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtanNvbi1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0Y5QTgyNSI+CiAgICA8cGF0aCBkPSJNMjAuMiAxMS44Yy0xLjYgMC0xLjcuNS0xLjcgMSAwIC40LjEuOS4xIDEuMy4xLjUuMS45LjEgMS4zIDAgMS43LTEuNCAyLjMtMy41IDIuM2gtLjl2LTEuOWguNWMxLjEgMCAxLjQgMCAxLjQtLjggMC0uMyAwLS42LS4xLTEgMC0uNC0uMS0uOC0uMS0xLjIgMC0xLjMgMC0xLjggMS4zLTItMS4zLS4yLTEuMy0uNy0xLjMtMiAwLS40LjEtLjguMS0xLjIuMS0uNC4xLS43LjEtMSAwLS44LS40LS43LTEuNC0uOGgtLjVWNC4xaC45YzIuMiAwIDMuNS43IDMuNSAyLjMgMCAuNC0uMS45LS4xIDEuMy0uMS41LS4xLjktLjEgMS4zIDAgLjUuMiAxIDEuNyAxdjEuOHpNMS44IDEwLjFjMS42IDAgMS43LS41IDEuNy0xIDAtLjQtLjEtLjktLjEtMS4zLS4xLS41LS4xLS45LS4xLTEuMyAwLTEuNiAxLjQtMi4zIDMuNS0yLjNoLjl2MS45aC0uNWMtMSAwLTEuNCAwLTEuNC44IDAgLjMgMCAuNi4xIDEgMCAuMi4xLjYuMSAxIDAgMS4zIDAgMS44LTEuMyAyQzYgMTEuMiA2IDExLjcgNiAxM2MwIC40LS4xLjgtLjEgMS4yLS4xLjMtLjEuNy0uMSAxIDAgLjguMy44IDEuNC44aC41djEuOWgtLjljLTIuMSAwLTMuNS0uNi0zLjUtMi4zIDAtLjQuMS0uOS4xLTEuMy4xLS41LjEtLjkuMS0xLjMgMC0uNS0uMi0xLTEuNy0xdi0xLjl6Ii8+CiAgICA8Y2lyY2xlIGN4PSIxMSIgY3k9IjEzLjgiIHI9IjIuMSIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSI4LjIiIHI9IjIuMSIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgPGcgY2xhc3M9ImpwLWp1cHl0ZXItaWNvbi1jb2xvciIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgIDxnIGNsYXNzPSJqcC1qdXB5dGVyLWljb24tY29sb3IiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launch: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMzIgMzIiIHdpZHRoPSIzMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yNiwyOEg2YTIuMDAyNywyLjAwMjcsMCwwLDEtMi0yVjZBMi4wMDI3LDIuMDAyNywwLDAsMSw2LDRIMTZWNkg2VjI2SDI2VjE2aDJWMjZBMi4wMDI3LDIuMDAyNywwLDAsMSwyNiwyOFoiLz4KICAgIDxwb2x5Z29uIHBvaW50cz0iMjAgMiAyMCA0IDI2LjU4NiA0IDE4IDEyLjU4NiAxOS40MTQgMTQgMjggNS40MTQgMjggMTIgMzAgMTIgMzAgMiAyMCAyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4K);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-move-down: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMTIuNDcxIDcuNTI4OTlDMTIuNzYzMiA3LjIzNjg0IDEyLjc2MzIgNi43NjMxNiAxMi40NzEgNi40NzEwMVY2LjQ3MTAxQzEyLjE3OSA2LjE3OTA1IDExLjcwNTcgNi4xNzg4NCAxMS40MTM1IDYuNDcwNTRMNy43NSAxMC4xMjc1VjEuNzVDNy43NSAxLjMzNTc5IDcuNDE0MjEgMSA3IDFWMUM2LjU4NTc5IDEgNi4yNSAxLjMzNTc5IDYuMjUgMS43NVYxMC4xMjc1TDIuNTk3MjYgNi40NjgyMkMyLjMwMzM4IDYuMTczODEgMS44MjY0MSA2LjE3MzU5IDEuNTMyMjYgNi40Njc3NFY2LjQ2Nzc0QzEuMjM4MyA2Ljc2MTcgMS4yMzgzIDcuMjM4MyAxLjUzMjI2IDcuNTMyMjZMNi4yOTI4OSAxMi4yOTI5QzYuNjgzNDIgMTIuNjgzNCA3LjMxNjU4IDEyLjY4MzQgNy43MDcxMSAxMi4yOTI5TDEyLjQ3MSA3LjUyODk5WiIgZmlsbD0iIzYxNjE2MSIvPgo8L3N2Zz4K);
  --jp-icon-move-up: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMS41Mjg5OSA2LjQ3MTAxQzEuMjM2ODQgNi43NjMxNiAxLjIzNjg0IDcuMjM2ODQgMS41Mjg5OSA3LjUyODk5VjcuNTI4OTlDMS44MjA5NSA3LjgyMDk1IDIuMjk0MjYgNy44MjExNiAyLjU4NjQ5IDcuNTI5NDZMNi4yNSAzLjg3MjVWMTIuMjVDNi4yNSAxMi42NjQyIDYuNTg1NzkgMTMgNyAxM1YxM0M3LjQxNDIxIDEzIDcuNzUgMTIuNjY0MiA3Ljc1IDEyLjI1VjMuODcyNUwxMS40MDI3IDcuNTMxNzhDMTEuNjk2NiA3LjgyNjE5IDEyLjE3MzYgNy44MjY0MSAxMi40Njc3IDcuNTMyMjZWNy41MzIyNkMxMi43NjE3IDcuMjM4MyAxMi43NjE3IDYuNzYxNyAxMi40Njc3IDYuNDY3NzRMNy43MDcxMSAxLjcwNzExQzcuMzE2NTggMS4zMTY1OCA2LjY4MzQyIDEuMzE2NTggNi4yOTI4OSAxLjcwNzExTDEuNTI4OTkgNi40NzEwMVoiIGZpbGw9IiM2MTYxNjEiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtbm90ZWJvb2staWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iLTEwIC0xMCAxMzEuMTYxMzYxNjk0MzM1OTQgMTMyLjM4ODk5OTkzODk2NDg0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzA2OTk4IiBkPSJNIDU0LjkxODc4NSw5LjE5Mjc0MjFlLTQgQyA1MC4zMzUxMzIsMC4wMjIyMTcyNyA0NS45NTc4NDYsMC40MTMxMzY5NyA0Mi4xMDYyODUsMS4wOTQ2NjkzIDMwLjc2MDA2OSwzLjA5OTE3MzEgMjguNzAwMDM2LDcuMjk0NzcxNCAyOC43MDAwMzUsMTUuMDMyMTY5IHYgMTAuMjE4NzUgaCAyNi44MTI1IHYgMy40MDYyNSBoIC0yNi44MTI1IC0xMC4wNjI1IGMgLTcuNzkyNDU5LDAgLTE0LjYxNTc1ODgsNC42ODM3MTcgLTE2Ljc0OTk5OTgsMTMuNTkzNzUgLTIuNDYxODE5OTgsMTAuMjEyOTY2IC0yLjU3MTAxNTA4LDE2LjU4NjAyMyAwLDI3LjI1IDEuOTA1OTI4Myw3LjkzNzg1MiA2LjQ1NzU0MzIsMTMuNTkzNzQ4IDE0LjI0OTk5OTgsMTMuNTkzNzUgaCA5LjIxODc1IHYgLTEyLjI1IGMgMCwtOC44NDk5MDIgNy42NTcxNDQsLTE2LjY1NjI0OCAxNi43NSwtMTYuNjU2MjUgaCAyNi43ODEyNSBjIDcuNDU0OTUxLDAgMTMuNDA2MjUzLC02LjEzODE2NCAxMy40MDYyNSwtMTMuNjI1IHYgLTI1LjUzMTI1IGMgMCwtNy4yNjYzMzg2IC02LjEyOTk4LC0xMi43MjQ3NzcxIC0xMy40MDYyNSwtMTMuOTM3NDk5NyBDIDY0LjI4MTU0OCwwLjMyNzk0Mzk3IDU5LjUwMjQzOCwtMC4wMjAzNzkwMyA1NC45MTg3ODUsOS4xOTI3NDIxZS00IFogbSAtMTQuNSw4LjIxODc1MDEyNTc5IGMgMi43Njk1NDcsMCA1LjAzMTI1LDIuMjk4NjQ1NiA1LjAzMTI1LDUuMTI0OTk5NiAtMmUtNiwyLjgxNjMzNiAtMi4yNjE3MDMsNS4wOTM3NSAtNS4wMzEyNSw1LjA5Mzc1IC0yLjc3OTQ3NiwtMWUtNiAtNS4wMzEyNSwtMi4yNzc0MTUgLTUuMDMxMjUsLTUuMDkzNzUgLTEwZS03LC0yLjgyNjM1MyAyLjI1MTc3NCwtNS4xMjQ5OTk2IDUuMDMxMjUsLTUuMTI0OTk5NiB6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2ZmZDQzYiIgZD0ibSA4NS42Mzc1MzUsMjguNjU3MTY5IHYgMTEuOTA2MjUgYyAwLDkuMjMwNzU1IC03LjgyNTg5NSwxNi45OTk5OTkgLTE2Ljc1LDE3IGggLTI2Ljc4MTI1IGMgLTcuMzM1ODMzLDAgLTEzLjQwNjI0OSw2LjI3ODQ4MyAtMTMuNDA2MjUsMTMuNjI1IHYgMjUuNTMxMjQ3IGMgMCw3LjI2NjM0NCA2LjMxODU4OCwxMS41NDAzMjQgMTMuNDA2MjUsMTMuNjI1MDA0IDguNDg3MzMxLDIuNDk1NjEgMTYuNjI2MjM3LDIuOTQ2NjMgMjYuNzgxMjUsMCA2Ljc1MDE1NSwtMS45NTQzOSAxMy40MDYyNTMsLTUuODg3NjEgMTMuNDA2MjUsLTEzLjYyNTAwNCBWIDg2LjUwMDkxOSBoIC0yNi43ODEyNSB2IC0zLjQwNjI1IGggMjYuNzgxMjUgMTMuNDA2MjU0IGMgNy43OTI0NjEsMCAxMC42OTYyNTEsLTUuNDM1NDA4IDEzLjQwNjI0MSwtMTMuNTkzNzUgMi43OTkzMywtOC4zOTg4ODYgMi42ODAyMiwtMTYuNDc1Nzc2IDAsLTI3LjI1IC0xLjkyNTc4LC03Ljc1NzQ0MSAtNS42MDM4NywtMTMuNTkzNzUgLTEzLjQwNjI0MSwtMTMuNTkzNzUgeiBtIC0xNS4wNjI1LDY0LjY1NjI1IGMgMi43Nzk0NzgsM2UtNiA1LjAzMTI1LDIuMjc3NDE3IDUuMDMxMjUsNS4wOTM3NDcgLTJlLTYsMi44MjYzNTQgLTIuMjUxNzc1LDUuMTI1MDA0IC01LjAzMTI1LDUuMTI1MDA0IC0yLjc2OTU1LDAgLTUuMDMxMjUsLTIuMjk4NjUgLTUuMDMxMjUsLTUuMTI1MDA0IDJlLTYsLTIuODE2MzMgMi4yNjE2OTcsLTUuMDkzNzQ3IDUuMDMxMjUsLTUuMDkzNzQ3IHoiLz4KPC9zdmc+Cg==);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-share: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTSAxOCAyIEMgMTYuMzU0OTkgMiAxNSAzLjM1NDk5MDQgMTUgNSBDIDE1IDUuMTkwOTUyOSAxNS4wMjE3OTEgNS4zNzcxMjI0IDE1LjA1NjY0MSA1LjU1ODU5MzggTCA3LjkyMTg3NSA5LjcyMDcwMzEgQyA3LjM5ODUzOTkgOS4yNzc4NTM5IDYuNzMyMDc3MSA5IDYgOSBDIDQuMzU0OTkwNCA5IDMgMTAuMzU0OTkgMyAxMiBDIDMgMTMuNjQ1MDEgNC4zNTQ5OTA0IDE1IDYgMTUgQyA2LjczMjA3NzEgMTUgNy4zOTg1Mzk5IDE0LjcyMjE0NiA3LjkyMTg3NSAxNC4yNzkyOTcgTCAxNS4wNTY2NDEgMTguNDM5NDUzIEMgMTUuMDIxNTU1IDE4LjYyMTUxNCAxNSAxOC44MDgzODYgMTUgMTkgQyAxNSAyMC42NDUwMSAxNi4zNTQ5OSAyMiAxOCAyMiBDIDE5LjY0NTAxIDIyIDIxIDIwLjY0NTAxIDIxIDE5IEMgMjEgMTcuMzU0OTkgMTkuNjQ1MDEgMTYgMTggMTYgQyAxNy4yNjc0OCAxNiAxNi42MDE1OTMgMTYuMjc5MzI4IDE2LjA3ODEyNSAxNi43MjI2NTYgTCA4Ljk0MzM1OTQgMTIuNTU4NTk0IEMgOC45NzgyMDk1IDEyLjM3NzEyMiA5IDEyLjE5MDk1MyA5IDEyIEMgOSAxMS44MDkwNDcgOC45NzgyMDk1IDExLjYyMjg3OCA4Ljk0MzM1OTQgMTEuNDQxNDA2IEwgMTYuMDc4MTI1IDcuMjc5Mjk2OSBDIDE2LjYwMTQ2IDcuNzIyMTQ2MSAxNy4yNjc5MjMgOCAxOCA4IEMgMTkuNjQ1MDEgOCAyMSA2LjY0NTAwOTYgMjEgNSBDIDIxIDMuMzU0OTkwNCAxOS42NDUwMSAyIDE4IDIgeiBNIDE4IDQgQyAxOC41NjQxMjkgNCAxOSA0LjQzNTg3MDYgMTkgNSBDIDE5IDUuNTY0MTI5NCAxOC41NjQxMjkgNiAxOCA2IEMgMTcuNDM1ODcxIDYgMTcgNS41NjQxMjk0IDE3IDUgQyAxNyA0LjQzNTg3MDYgMTcuNDM1ODcxIDQgMTggNCB6IE0gNiAxMSBDIDYuNTY0MTI5NCAxMSA3IDExLjQzNTg3MSA3IDEyIEMgNyAxMi41NjQxMjkgNi41NjQxMjk0IDEzIDYgMTMgQyA1LjQzNTg3MDYgMTMgNSAxMi41NjQxMjkgNSAxMiBDIDUgMTEuNDM1ODcxIDUuNDM1ODcwNiAxMSA2IDExIHogTSAxOCAxOCBDIDE4LjU2NDEyOSAxOCAxOSAxOC40MzU4NzEgMTkgMTkgQyAxOSAxOS41NjQxMjkgMTguNTY0MTI5IDIwIDE4IDIwIEMgMTcuNDM1ODcxIDIwIDE3IDE5LjU2NDEyOSAxNyAxOSBDIDE3IDE4LjQzNTg3MSAxNy40MzU4NzEgMTggMTggMTggeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1iYWNrZ3JvdW5kLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgd2lkdGg9IjIwIiBoZWlnaHQ9IjIwIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyIDIpIiBmaWxsPSIjMzMzMzMzIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUtaW52ZXJzZSIgZD0iTTUuMDU2NjQgOC43NjE3MkM1LjA1NjY0IDguNTk3NjYgNS4wMzEyNSA4LjQ1MzEyIDQuOTgwNDcgOC4zMjgxMkM0LjkzMzU5IDguMTk5MjIgNC44NTU0NyA4LjA4MjAzIDQuNzQ2MDkgNy45NzY1NkM0LjY0MDYyIDcuODcxMDkgNC41IDcuNzc1MzkgNC4zMjQyMiA3LjY4OTQ1QzQuMTUyMzQgNy41OTk2MSAzLjk0MzM2IDcuNTExNzIgMy42OTcyNyA3LjQyNTc4QzMuMzAyNzMgNy4yODUxNiAyLjk0MzM2IDcuMTM2NzIgMi42MTkxNCA2Ljk4MDQ3QzIuMjk0OTIgNi44MjQyMiAyLjAxNzU4IDYuNjQyNTggMS43ODcxMSA2LjQzNTU1QzEuNTYwNTUgNi4yMjg1MiAxLjM4NDc3IDUuOTg4MjggMS4yNTk3NyA1LjcxNDg0QzEuMTM0NzcgNS40Mzc1IDEuMDcyMjcgNS4xMDkzOCAxLjA3MjI3IDQuNzMwNDdDMS4wNzIyNyA0LjM5ODQ0IDEuMTI4OTEgNC4wOTU3IDEuMjQyMTkgMy44MjIyN0MxLjM1NTQ3IDMuNTQ0OTIgMS41MTU2MiAzLjMwNDY5IDEuNzIyNjYgMy4xMDE1NkMxLjkyOTY5IDIuODk4NDQgMi4xNzk2OSAyLjczNDM3IDIuNDcyNjYgMi42MDkzOEMyLjc2NTYyIDIuNDg0MzggMy4wOTE4IDIuNDA0MyAzLjQ1MTE3IDIuMzY5MTRWMS4xMDkzOEg0LjM4ODY3VjIuMzgwODZDNC43NDAyMyAyLjQyNzczIDUuMDU2NjQgMi41MjM0NCA1LjMzNzg5IDIuNjY3OTdDNS42MTkxNCAyLjgxMjUgNS44NTc0MiAzLjAwMTk1IDYuMDUyNzMgMy4yMzYzM0M2LjI1MTk1IDMuNDY2OCA2LjQwNDMgMy43NDAyMyA2LjUwOTc3IDQuMDU2NjRDNi42MTkxNCA0LjM2OTE0IDYuNjczODMgNC43MjA3IDYuNjczODMgNS4xMTEzM0g1LjA0NDkyQzUuMDQ0OTIgNC42Mzg2NyA0LjkzNzUgNC4yODEyNSA0LjcyMjY2IDQuMDM5MDZDNC41MDc4MSAzLjc5Mjk3IDQuMjE2OCAzLjY2OTkyIDMuODQ5NjEgMy42Njk5MkMzLjY1MDM5IDMuNjY5OTIgMy40NzY1NiAzLjY5NzI3IDMuMzI4MTIgMy43NTE5NUMzLjE4MzU5IDMuODAyNzMgMy4wNjQ0NSAzLjg3Njk1IDIuOTcwNyAzLjk3NDYxQzIuODc2OTUgNC4wNjgzNiAyLjgwNjY0IDQuMTc5NjkgMi43NTk3NyA0LjMwODU5QzIuNzE2OCA0LjQzNzUgMi42OTUzMSA0LjU3ODEyIDIuNjk1MzEgNC43MzA0N0MyLjY5NTMxIDQuODgyODEgMi43MTY4IDUuMDE5NTMgMi43NTk3NyA1LjE0MDYyQzIuODA2NjQgNS4yNTc4MSAyLjg4MjgxIDUuMzY3MTkgMi45ODgyOCA1LjQ2ODc1QzMuMDk3NjYgNS41NzAzMSAzLjI0MDIzIDUuNjY3OTcgMy40MTYwMiA1Ljc2MTcyQzMuNTkxOCA1Ljg1MTU2IDMuODEwNTUgNS45NDMzNiA0LjA3MjI3IDYuMDM3MTFDNC40NjY4IDYuMTg1NTUgNC44MjQyMiA2LjMzOTg0IDUuMTQ0NTMgNi41QzUuNDY0ODQgNi42NTYyNSA1LjczODI4IDYuODM5ODQgNS45NjQ4NCA3LjA1MDc4QzYuMTk1MzEgNy4yNTc4MSA2LjM3MTA5IDcuNSA2LjQ5MjE5IDcuNzc3MzRDNi42MTcxOSA4LjA1MDc4IDYuNjc5NjkgOC4zNzUgNi42Nzk2OSA4Ljc1QzYuNjc5NjkgOS4wOTM3NSA2LjYyMzA1IDkuNDA0MyA2LjUwOTc3IDkuNjgxNjRDNi4zOTY0OCA5Ljk1NTA4IDYuMjM0MzggMTAuMTkxNCA2LjAyMzQ0IDEwLjM5MDZDNS44MTI1IDEwLjU4OTggNS41NTg1OSAxMC43NSA1LjI2MTcyIDEwLjg3MTFDNC45NjQ4NCAxMC45ODgzIDQuNjMyODEgMTEuMDY0NSA0LjI2NTYyIDExLjA5OTZWMTIuMjQ4SDMuMzMzOThWMTEuMDk5NkMzLjAwMTk1IDExLjA2ODQgMi42Nzk2OSAxMC45OTYxIDIuMzY3MTkgMTAuODgyOEMyLjA1NDY5IDEwLjc2NTYgMS43NzczNCAxMC41OTc3IDEuNTM1MTYgMTAuMzc4OUMxLjI5Njg4IDEwLjE2MDIgMS4xMDU0NyA5Ljg4NDc3IDAuOTYwOTM4IDkuNTUyNzNDMC44MTY0MDYgOS4yMTY4IDAuNzQ0MTQxIDguODE0NDUgMC43NDQxNDEgOC4zNDU3SDIuMzc4OTFDMi4zNzg5MSA4LjYyNjk1IDIuNDE5OTIgOC44NjMyOCAyLjUwMTk1IDkuMDU0NjlDMi41ODM5OCA5LjI0MjE5IDIuNjg5NDUgOS4zOTI1OCAyLjgxODM2IDkuNTA1ODZDMi45NTExNyA5LjYxNTIzIDMuMTAxNTYgOS42OTMzNiAzLjI2OTUzIDkuNzQwMjNDMy40Mzc1IDkuNzg3MTEgMy42MDkzOCA5LjgxMDU1IDMuNzg1MTYgOS44MTA1NUM0LjIwMzEyIDkuODEwNTUgNC41MTk1MyA5LjcxMjg5IDQuNzM0MzggOS41MTc1OEM0Ljk0OTIyIDkuMzIyMjcgNS4wNTY2NCA5LjA3MDMxIDUuMDU2NjQgOC43NjE3MlpNMTMuNDE4IDEyLjI3MTVIOC4wNzQyMlYxMUgxMy40MThWMTIuMjcxNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMuOTUyNjQgNikiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgo=);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtdGV4dC1lZGl0b3ItaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xNSAxNUgzdjJoMTJ2LTJ6bTAtOEgzdjJoMTJWN3pNMyAxM2gxOHYtMkgzdjJ6bTAgOGgxOHYtMkgzdjJ6TTMgM3YyaDE4VjNIM3oiLz4KPC9zdmc+Cg==);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-user: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE2IDdhNCA0IDAgMTEtOCAwIDQgNCAwIDAxOCAwek0xMiAxNGE3IDcgMCAwMC03IDdoMTRhNyA3IDAgMDAtNy03eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-users: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDM2IDI0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogPGcgY2xhc3M9ImpwLWljb24zIiB0cmFuc2Zvcm09Im1hdHJpeCgxLjczMjcgMCAwIDEuNzMyNyAtMy42MjgyIC4wOTk1NzcpIiBmaWxsPSIjNjE2MTYxIj4KICA8cGF0aCB0cmFuc2Zvcm09Im1hdHJpeCgxLjUsMCwwLDEuNSwwLC02KSIgZD0ibTEyLjE4NiA3LjUwOThjLTEuMDUzNSAwLTEuOTc1NyAwLjU2NjUtMi40Nzg1IDEuNDEwMiAwLjc1MDYxIDAuMzEyNzcgMS4zOTc0IDAuODI2NDggMS44NzMgMS40NzI3aDMuNDg2M2MwLTEuNTkyLTEuMjg4OS0yLjg4MjgtMi44ODA5LTIuODgyOHoiLz4KICA8cGF0aCBkPSJtMjAuNDY1IDIuMzg5NWEyLjE4ODUgMi4xODg1IDAgMCAxLTIuMTg4NCAyLjE4ODUgMi4xODg1IDIuMTg4NSAwIDAgMS0yLjE4ODUtMi4xODg1IDIuMTg4NSAyLjE4ODUgMCAwIDEgMi4xODg1LTIuMTg4NSAyLjE4ODUgMi4xODg1IDAgMCAxIDIuMTg4NCAyLjE4ODV6Ii8+CiAgPHBhdGggdHJhbnNmb3JtPSJtYXRyaXgoMS41LDAsMCwxLjUsMCwtNikiIGQ9Im0zLjU4OTggOC40MjE5Yy0xLjExMjYgMC0yLjAxMzcgMC45MDExMS0yLjAxMzcgMi4wMTM3aDIuODE0NWMwLjI2Nzk3LTAuMzczMDkgMC41OTA3LTAuNzA0MzUgMC45NTg5OC0wLjk3ODUyLTAuMzQ0MzMtMC42MTY4OC0xLjAwMzEtMS4wMzUyLTEuNzU5OC0xLjAzNTJ6Ii8+CiAgPHBhdGggZD0ibTYuOTE1NCA0LjYyM2ExLjUyOTQgMS41Mjk0IDAgMCAxLTEuNTI5NCAxLjUyOTQgMS41Mjk0IDEuNTI5NCAwIDAgMS0xLjUyOTQtMS41Mjk0IDEuNTI5NCAxLjUyOTQgMCAwIDEgMS41Mjk0LTEuNTI5NCAxLjUyOTQgMS41Mjk0IDAgMCAxIDEuNTI5NCAxLjUyOTR6Ii8+CiAgPHBhdGggZD0ibTYuMTM1IDEzLjUzNWMwLTMuMjM5MiAyLjYyNTktNS44NjUgNS44NjUtNS44NjUgMy4yMzkyIDAgNS44NjUgMi42MjU5IDUuODY1IDUuODY1eiIvPgogIDxjaXJjbGUgY3g9IjEyIiBjeT0iMy43Njg1IiByPSIyLjk2ODUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-word: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KIDxnIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzQxNDE0MSI+CiAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiA8L2c+CiA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSguNDMgLjA0MDEpIiBmaWxsPSIjZmZmIj4KICA8cGF0aCBkPSJtNC4xNCA4Ljc2cTAuMDY4Mi0xLjg5IDIuNDItMS44OSAxLjE2IDAgMS42OCAwLjQyIDAuNTY3IDAuNDEgMC41NjcgMS4xNnYzLjQ3cTAgMC40NjIgMC41MTQgMC40NjIgMC4xMDMgMCAwLjItMC4wMjMxdjAuNzE0cS0wLjM5OSAwLjEwMy0wLjY1MSAwLjEwMy0wLjQ1MiAwLTAuNjkzLTAuMjItMC4yMzEtMC4yLTAuMjg0LTAuNjYyLTAuOTU2IDAuODcyLTIgMC44NzItMC45MDMgMC0xLjQ3LTAuNDcyLTAuNTI1LTAuNDcyLTAuNTI1LTEuMjYgMC0wLjI2MiAwLjA0NTItMC40NzIgMC4wNTY3LTAuMjIgMC4xMTYtMC4zNzggMC4wNjgyLTAuMTY4IDAuMjMxLTAuMzA0IDAuMTU4LTAuMTQ3IDAuMjYyLTAuMjQyIDAuMTE2LTAuMDkxNCAwLjM2OC0wLjE2OCAwLjI2Mi0wLjA5MTQgMC4zOTktMC4xMjYgMC4xMzYtMC4wNDUyIDAuNDcyLTAuMTAzIDAuMzM2LTAuMDU3OCAwLjUwNC0wLjA3OTggMC4xNTgtMC4wMjMxIDAuNTY3LTAuMDc5OCAwLjU1Ni0wLjA2ODIgMC43NzctMC4yMjEgMC4yMi0wLjE1MiAwLjIyLTAuNDQxdi0wLjI1MnEwLTAuNDMtMC4zNTctMC42NjItMC4zMzYtMC4yMzEtMC45NzYtMC4yMzEtMC42NjIgMC0wLjk5OCAwLjI2Mi0wLjMzNiAwLjI1Mi0wLjM5OSAwLjc5OHptMS44OSAzLjY4cTAuNzg4IDAgMS4yNi0wLjQxIDAuNTA0LTAuNDIgMC41MDQtMC45MDN2LTEuMDVxLTAuMjg0IDAuMTM2LTAuODYxIDAuMjMxLTAuNTY3IDAuMDkxNC0wLjk4NyAwLjE1OC0wLjQyIDAuMDY4Mi0wLjc2NiAwLjMyNi0wLjMzNiAwLjI1Mi0wLjMzNiAwLjcwNHQwLjMwNCAwLjcwNCAwLjg2MSAwLjI1MnoiIHN0cm9rZS13aWR0aD0iMS4wNSIvPgogIDxwYXRoIGQ9Im0xMCA0LjU2aDAuOTQ1djMuMTVxMC42NTEtMC45NzYgMS44OS0wLjk3NiAxLjE2IDAgMS44OSAwLjg0IDAuNjgyIDAuODQgMC42ODIgMi4zMSAwIDEuNDctMC43MDQgMi40Mi0wLjcwNCAwLjg4Mi0xLjg5IDAuODgyLTEuMjYgMC0xLjg5LTEuMDJ2MC43NjZoLTAuODV6bTIuNjIgMy4wNHEtMC43NDYgMC0xLjE2IDAuNjQtMC40NTIgMC42My0wLjQ1MiAxLjY4IDAgMS4wNSAwLjQ1MiAxLjY4dDEuMTYgMC42M3EwLjc3NyAwIDEuMjYtMC42MyAwLjQ5NC0wLjY0IDAuNDk0LTEuNjggMC0xLjA1LTAuNDcyLTEuNjgtMC40NjItMC42NC0xLjI2LTAuNjR6IiBzdHJva2Utd2lkdGg9IjEuMDUiLz4KICA8cGF0aCBkPSJtMi43MyAxNS44IDEzLjYgMC4wMDgxYzAuMDA2OSAwIDAtMi42IDAtMi42IDAtMC4wMDc4LTEuMTUgMC0xLjE1IDAtMC4wMDY5IDAtMC4wMDgzIDEuNS0wLjAwODMgMS41LTJlLTMgLTAuMDAxNC0xMS4zLTAuMDAxNC0xMS4zLTAuMDAxNGwtMC4wMDU5Mi0xLjVjMC0wLjAwNzgtMS4xNyAwLjAwMTMtMS4xNyAwLjAwMTN6IiBzdHJva2Utd2lkdGg9Ii45NzUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddAboveIcon {
  background-image: var(--jp-icon-add-above);
}

.jp-AddBelowIcon {
  background-image: var(--jp-icon-add-below);
}

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}

.jp-BellIcon {
  background-image: var(--jp-icon-bell);
}

.jp-BugDotIcon {
  background-image: var(--jp-icon-bug-dot);
}

.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}

.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}

.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}

.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}

.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}

.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}

.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}

.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}

.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}

.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}

.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}

.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}

.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}

.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}

.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}

.jp-CodeCheckIcon {
  background-image: var(--jp-icon-code-check);
}

.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}

.jp-CollapseAllIcon {
  background-image: var(--jp-icon-collapse-all);
}

.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}

.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}

.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}

.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}

.jp-DeleteIcon {
  background-image: var(--jp-icon-delete);
}

.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}

.jp-DuplicateIcon {
  background-image: var(--jp-icon-duplicate);
}

.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}

.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}

.jp-ErrorIcon {
  background-image: var(--jp-icon-error);
}

.jp-ExpandAllIcon {
  background-image: var(--jp-icon-expand-all);
}

.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}

.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}

.jp-FileIcon {
  background-image: var(--jp-icon-file);
}

.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}

.jp-FilterDotIcon {
  background-image: var(--jp-icon-filter-dot);
}

.jp-FilterIcon {
  background-image: var(--jp-icon-filter);
}

.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}

.jp-FolderFavoriteIcon {
  background-image: var(--jp-icon-folder-favorite);
}

.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}

.jp-HomeIcon {
  background-image: var(--jp-icon-home);
}

.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}

.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}

.jp-InfoIcon {
  background-image: var(--jp-icon-info);
}

.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}

.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}

.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}

.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}

.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}

.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}

.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}

.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}

.jp-LaunchIcon {
  background-image: var(--jp-icon-launch);
}

.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}

.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}

.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}

.jp-ListIcon {
  background-image: var(--jp-icon-list);
}

.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}

.jp-MoveDownIcon {
  background-image: var(--jp-icon-move-down);
}

.jp-MoveUpIcon {
  background-image: var(--jp-icon-move-up);
}

.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}

.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}

.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}

.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}

.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}

.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}

.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}

.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}

.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}

.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}

.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}

.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}

.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}

.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}

.jp-RunIcon {
  background-image: var(--jp-icon-run);
}

.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}

.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}

.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}

.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}

.jp-ShareIcon {
  background-image: var(--jp-icon-share);
}

.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}

.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}

.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}

.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}

.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}

.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}

.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}

.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}

.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}

.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}

.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}

.jp-UserIcon {
  background-image: var(--jp-icon-user);
}

.jp-UsersIcon {
  background-image: var(--jp-icon-users);
}

.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}

.jp-WordIcon {
  background-image: var(--jp-icon-word);
}

.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.lm-TabBar .lm-TabBar-addButton {
  align-items: center;
  display: flex;
  padding: 4px;
  padding-bottom: 5px;
  margin-right: 1px;
  background-color: var(--jp-layout-color2);
}

.lm-TabBar .lm-TabBar-addButton:hover {
  background-color: var(--jp-layout-color1);
}

.lm-DockPanel-tabBar .lm-TabBar-tab {
  width: var(--jp-private-horizontal-tab-width);
}

.lm-DockPanel-tabBar .lm-TabBar-content {
  flex: unset;
}

.lm-DockPanel-tabBar[data-orientation='horizontal'] {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}

/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}

.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}

.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}

.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}

.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}

.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}

.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}

.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}

.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}

/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}

.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}

.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}

.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}

.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}

.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}

.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}

/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

.jp-icon-dot[fill] {
  fill: var(--jp-warn-color0);
}

.jp-jupyter-icon-color[fill] {
  fill: var(--jp-jupyter-icon-color, var(--jp-warn-color0));
}

.jp-notebook-icon-color[fill] {
  fill: var(--jp-notebook-icon-color, var(--jp-warn-color0));
}

.jp-json-icon-color[fill] {
  fill: var(--jp-json-icon-color, var(--jp-warn-color1));
}

.jp-console-icon-color[fill] {
  fill: var(--jp-console-icon-color, white);
}

.jp-console-icon-background-color[fill] {
  fill: var(--jp-console-icon-background-color, var(--jp-brand-color1));
}

.jp-terminal-icon-color[fill] {
  fill: var(--jp-terminal-icon-color, var(--jp-layout-color2));
}

.jp-terminal-icon-background-color[fill] {
  fill: var(
    --jp-terminal-icon-background-color,
    var(--jp-inverse-layout-color2)
  );
}

.jp-text-editor-icon-color[fill] {
  fill: var(--jp-text-editor-icon-color, var(--jp-inverse-layout-color3));
}

.jp-inspector-icon-color[fill] {
  fill: var(--jp-inspector-icon-color, var(--jp-inverse-layout-color3));
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* stylelint-disable selector-max-class, selector-max-compound-selectors */

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}

.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* stylelint-enable selector-max-class, selector-max-compound-selectors */

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) .jp-icon-hoverShow-content {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FormGroup-content fieldset {
  border: none;
  padding: 0;
  min-width: 0;
  width: 100%;
}

/* stylelint-disable selector-max-type */

.jp-FormGroup-content fieldset .jp-inputFieldWrapper input,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper select,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper textarea {
  font-size: var(--jp-content-font-size2);
  border-color: var(--jp-input-border-color);
  border-style: solid;
  border-radius: var(--jp-border-radius);
  border-width: 1px;
  padding: 6px 8px;
  background: none;
  color: var(--jp-ui-font-color0);
  height: inherit;
}

.jp-FormGroup-content fieldset input[type='checkbox'] {
  position: relative;
  top: 2px;
  margin-left: 0;
}

.jp-FormGroup-content button.jp-mod-styled {
  cursor: pointer;
}

.jp-FormGroup-content .checkbox label {
  cursor: pointer;
  font-size: var(--jp-content-font-size1);
}

.jp-FormGroup-content .jp-root > fieldset > legend {
  display: none;
}

.jp-FormGroup-content .jp-root > fieldset > p {
  display: none;
}

/** copy of `input.jp-mod-styled:focus` style */
.jp-FormGroup-content fieldset input:focus,
.jp-FormGroup-content fieldset select:focus {
  -moz-outline-radius: unset;
  outline: var(--jp-border-width) solid var(--md-blue-500);
  outline-offset: -1px;
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FormGroup-content fieldset input:hover:not(:focus),
.jp-FormGroup-content fieldset select:hover:not(:focus) {
  background-color: var(--jp-border-color2);
}

/* stylelint-enable selector-max-type */

.jp-FormGroup-content .checkbox .field-description {
  /* Disable default description field for checkbox:
   because other widgets do not have description fields,
   we add descriptions to each widget on the field level.
  */
  display: none;
}

.jp-FormGroup-content #root__description {
  display: none;
}

.jp-FormGroup-content .jp-modifiedIndicator {
  width: 5px;
  background-color: var(--jp-brand-color2);
  margin-top: 0;
  margin-left: calc(var(--jp-private-settingeditor-modifier-indent) * -1);
  flex-shrink: 0;
}

.jp-FormGroup-content .jp-modifiedIndicator.jp-errorIndicator {
  background-color: var(--jp-error-color0);
  margin-right: 0.5em;
}

/* RJSF ARRAY style */

.jp-arrayFieldWrapper legend {
  font-size: var(--jp-content-font-size2);
  color: var(--jp-ui-font-color0);
  flex-basis: 100%;
  padding: 4px 0;
  font-weight: var(--jp-content-heading-font-weight);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-arrayFieldWrapper .field-description {
  padding: 4px 0;
  white-space: pre-wrap;
}

.jp-arrayFieldWrapper .array-item {
  width: 100%;
  border: 1px solid var(--jp-border-color2);
  border-radius: 4px;
  margin: 4px;
}

.jp-ArrayOperations {
  display: flex;
  margin-left: 8px;
}

.jp-ArrayOperationsButton {
  margin: 2px;
}

.jp-ArrayOperationsButton .jp-icon3[fill] {
  fill: var(--jp-ui-font-color0);
}

button.jp-ArrayOperationsButton.jp-mod-styled:disabled {
  cursor: not-allowed;
  opacity: 0.5;
}

/* RJSF form validation error */

.jp-FormGroup-content .validationErrors {
  color: var(--jp-error-color0);
}

/* Hide panel level error as duplicated the field level error */
.jp-FormGroup-content .panel.errors {
  display: none;
}

/* RJSF normal content (settings-editor) */

.jp-FormGroup-contentNormal {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-FormGroup-contentItem {
  margin-left: 7px;
  color: var(--jp-ui-font-color0);
}

.jp-FormGroup-contentNormal .jp-FormGroup-description {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-default {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-fieldLabel {
  font-size: var(--jp-content-font-size1);
  font-weight: normal;
  min-width: 120px;
}

.jp-FormGroup-contentNormal fieldset:not(:first-child) {
  margin-left: 7px;
}

.jp-FormGroup-contentNormal .field-array-of-string .array-item {
  /* Display `jp-ArrayOperations` buttons side-by-side with content except
    for small screens where flex-wrap will place them one below the other.
  */
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-objectFieldWrapper .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

/* RJSF compact content (metadata-form) */

.jp-FormGroup-content.jp-FormGroup-contentCompact {
  width: 100%;
}

.jp-FormGroup-contentCompact .form-group {
  display: flex;
  padding: 0.5em 0.2em 0.5em 0;
}

.jp-FormGroup-contentCompact
  .jp-FormGroup-compactTitle
  .jp-FormGroup-description {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color2);
}

.jp-FormGroup-contentCompact .jp-FormGroup-fieldLabel {
  padding-bottom: 0.3em;
}

.jp-FormGroup-contentCompact .jp-inputFieldWrapper .form-control {
  width: 100%;
  box-sizing: border-box;
}

.jp-FormGroup-contentCompact .jp-arrayFieldWrapper .jp-FormGroup-compactTitle {
  padding-bottom: 7px;
}

.jp-FormGroup-contentCompact
  .jp-objectFieldWrapper
  .jp-objectFieldWrapper
  .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

.jp-FormGroup-contentCompact ul.error-detail {
  margin-block-start: 0.5em;
  margin-block-end: 0.5em;
  padding-inline-start: 1em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-SidePanel {
  display: flex;
  flex-direction: column;
  min-width: var(--jp-sidebar-min-width);
  overflow-y: auto;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size1);
}

.jp-SidePanel-header {
  flex: 0 0 auto;
  display: flex;
  border-bottom: var(--jp-border-width) solid var(--jp-border-color2);
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin: 0;
  padding: 2px;
  text-transform: uppercase;
}

.jp-SidePanel-toolbar {
  flex: 0 0 auto;
}

.jp-SidePanel-content {
  flex: 1 1 auto;
}

.jp-SidePanel-toolbar,
.jp-AccordionPanel-toolbar {
  height: var(--jp-private-toolbar-height);
}

.jp-SidePanel-toolbar.jp-Toolbar-micro {
  display: none;
}

.lm-AccordionPanel .jp-AccordionPanel-title {
  box-sizing: border-box;
  line-height: 25px;
  margin: 0;
  display: flex;
  align-items: center;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  font-size: var(--jp-ui-font-size0);
}

.jp-AccordionPanel-title {
  cursor: pointer;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  text-transform: uppercase;
}

.lm-AccordionPanel[data-orientation='horizontal'] > .jp-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleLabel {
  user-select: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleCollapser {
  transform: rotate(-90deg);
  margin: auto 0;
  height: 16px;
}

.jp-AccordionPanel-title.lm-mod-expanded .lm-AccordionPanel-titleCollapser {
  transform: rotate(0deg);
}

.lm-AccordionPanel .jp-AccordionPanel-toolbar {
  background: none;
  box-shadow: none;
  border: none;
  margin-left: auto;
}

.lm-AccordionPanel .lm-SplitPanel-handle:hover {
  background: var(--jp-layout-color3);
}

.jp-text-truncated {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent::before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent::after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper:not(.multiple) {
  height: 28px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

select.jp-mod-styled:not([multiple]) {
  height: 32px;
}

select.jp-mod-styled[multiple] {
  max-height: 200px;
  overflow-y: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
  font-family: var(--jp-ui-font-family);
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-switch-color, var(--jp-border-color1));
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-switch-true-position-color, var(--jp-warn-color0));
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 8;
  overflow-x: hidden;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0;
  margin: 0;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0 6px;
  margin: 0;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent > span {
  padding: 0;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-WindowedPanel-outer {
  position: relative;
  overflow-y: auto;
}

.jp-WindowedPanel-inner {
  position: relative;
}

.jp-WindowedPanel-window {
  position: absolute;
  left: 0;
  right: 0;
  overflow: visible;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

body {
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
}

/* Disable native link decoration styles everywhere outside of dialog boxes */
a {
  text-decoration: unset;
  color: unset;
}

a:hover {
  text-decoration: unset;
  color: unset;
}

/* Accessibility for links inside dialog box text */
.jp-Dialog-content a {
  text-decoration: revert;
  color: var(--jp-content-link-color);
}

.jp-Dialog-content a:hover {
  text-decoration: revert;
}

/* Styles for ui-components */
.jp-Button {
  color: var(--jp-ui-font-color2);
  border-radius: var(--jp-border-radius);
  padding: 0 12px;
  font-size: var(--jp-ui-font-size1);

  /* Copy from blueprint 3 */
  display: inline-flex;
  flex-direction: row;
  border: none;
  cursor: pointer;
  align-items: center;
  justify-content: center;
  text-align: left;
  vertical-align: middle;
  min-height: 30px;
  min-width: 30px;
}

.jp-Button:disabled {
  cursor: not-allowed;
}

.jp-Button:empty {
  padding: 0 !important;
}

.jp-Button.jp-mod-small {
  min-height: 24px;
  min-width: 24px;
  font-size: 12px;
  padding: 0 7px;
}

/* Use our own theme for hover styles */
.jp-Button.jp-mod-minimal:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Button.jp-mod-minimal {
  background: none;
}

.jp-InputGroup {
  display: block;
  position: relative;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border: none;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
  padding-bottom: 0;
  padding-top: 0;
  padding-left: 10px;
  padding-right: 28px;
  position: relative;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  font-size: 14px;
  font-weight: 400;
  height: 30px;
  line-height: 30px;
  outline: none;
  vertical-align: middle;
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input:disabled {
  cursor: not-allowed;
  resize: block;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input:disabled ~ span {
  cursor: not-allowed;
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color2);
}

.jp-InputGroupAction {
  position: absolute;
  bottom: 1px;
  right: 0;
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
  cursor: not-allowed;
  resize: block;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled ~ span {
  cursor: not-allowed;
}

/* Use our own theme for hover and option styles */
/* stylelint-disable-next-line selector-max-type */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}

select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-StatusBar-Widget {
  display: flex;
  align-items: center;
  background: var(--jp-layout-color2);
  min-height: var(--jp-statusbar-height);
  justify-content: space-between;
  padding: 0 10px;
}

.jp-StatusBar-Left {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-StatusBar-Middle {
  display: flex;
  align-items: center;
}

.jp-StatusBar-Right {
  display: flex;
  align-items: center;
  flex-direction: row-reverse;
}

.jp-StatusBar-Item {
  max-height: var(--jp-statusbar-height);
  margin: 0 2px;
  height: var(--jp-statusbar-height);
  white-space: nowrap;
  text-overflow: ellipsis;
  color: var(--jp-ui-font-color1);
  padding: 0 6px;
}

.jp-mod-highlighted:hover {
  background-color: var(--jp-layout-color3);
}

.jp-mod-clicked {
  background-color: var(--jp-brand-color1);
}

.jp-mod-clicked:hover {
  background-color: var(--jp-brand-color0);
}

.jp-mod-clicked .jp-StatusBar-TextItem {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-StatusBar-HoverItem {
  box-shadow: '0px 4px 4px rgba(0, 0, 0, 0.25)';
}

.jp-StatusBar-TextItem {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  line-height: 24px;
  color: var(--jp-ui-font-color1);
}

.jp-StatusBar-GroupItem {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-Statusbar-ProgressCircle svg {
  display: block;
  margin: 0 auto;
  width: 16px;
  height: 24px;
  align-self: normal;
}

.jp-Statusbar-ProgressCircle path {
  fill: var(--jp-inverse-layout-color3);
}

.jp-Statusbar-ProgressBar-progress-bar {
  height: 10px;
  width: 100px;
  border: solid 0.25px var(--jp-brand-color2);
  border-radius: 3px;
  overflow: hidden;
  align-self: center;
}

.jp-Statusbar-ProgressBar-progress-bar > div {
  background-color: var(--jp-brand-color2);
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 14px;
  color: #fff;
  text-align: center;
  animation: jp-Statusbar-ExecutionTime-progress-bar 2s linear infinite;
}

.jp-Statusbar-ProgressBar-progress-bar p {
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  line-height: 10px;
  width: 100px;
}

@keyframes jp-Statusbar-ExecutionTime-progress-bar {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 40px 40px;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty::after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px 24px 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-content.jp-Dialog-content-small {
  max-width: 500px;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus {
  outline: 1px solid var(--jp-accept-color-normal, var(--jp-brand-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus {
  outline: 1px solid var(--jp-warn-color-normal, var(--jp-error-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline: 1px solid var(--jp-reject-color-normal, var(--md-grey-600));
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-checkbox {
  padding-right: 5px;
}

.jp-Dialog-checkbox > input:focus-visible {
  outline: 1px solid var(--jp-input-active-border-color);
  outline-offset: 1px;
}

.jp-Dialog-spacer {
  flex: 1 1 auto;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error {
  padding: 6px;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error > pre {
  width: auto;
  padding: 10px;
  background: var(--jp-error-color3);
  border: var(--jp-border-width) solid var(--jp-error-color1);
  border-radius: var(--jp-border-radius);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  white-space: pre-wrap;
  word-wrap: break-word;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;
  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;
  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #a0f;
  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;
  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;
  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;
  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;
  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;
  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;
  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;
  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;
  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;
  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ff0;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;
  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;
  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;
  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;
  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;
  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;
  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0;
  padding: 0;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}

.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}

.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}

.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}

.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}

.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}

.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}

.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}

.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}

.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}

.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}

.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}

.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}

.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}

.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}

.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}

.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);

  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

/* stylelint-disable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0;
}

/* stylelint-enable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  table-layout: fixed;
  margin-left: auto;
  margin-bottom: 1em;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}

[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}

.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}

.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}

.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}

.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}

.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}

.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}

.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}

.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: var(--jp-ui-font-size0);
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-cursor-backdrop {
  position: fixed;
  width: 200px;
  height: 200px;
  margin-top: -100px;
  margin-left: -100px;
  will-change: transform;
  z-index: 100;
}

.lm-mod-drag-image {
  will-change: transform;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-lineFormSearch {
  padding: 4px 12px;
  background-color: var(--jp-layout-color2);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
  font-size: var(--jp-ui-font-size1);
}

.jp-lineFormCaption {
  font-size: var(--jp-ui-font-size0);
  line-height: var(--jp-ui-font-size1);
  margin-top: 4px;
  color: var(--jp-ui-font-color0);
}

.jp-baseLineForm {
  border: none;
  border-radius: 0;
  position: absolute;
  background-size: 16px;
  background-repeat: no-repeat;
  background-position: center;
  outline: none;
}

.jp-lineFormButtonContainer {
  top: 4px;
  right: 8px;
  height: 24px;
  padding: 0 12px;
  width: 12px;
}

.jp-lineFormButtonIcon {
  top: 0;
  right: 0;
  background-color: var(--jp-brand-color1);
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  padding: 4px 6px;
}

.jp-lineFormButton {
  top: 0;
  right: 0;
  background-color: transparent;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

.jp-lineFormWrapper {
  overflow: hidden;
  padding: 0 8px;
  border: 1px solid var(--jp-border-color0);
  background-color: var(--jp-input-active-background);
  height: 22px;
}

.jp-lineFormWrapperFocusWithin {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-lineFormInput {
  background: transparent;
  width: 200px;
  height: 100%;
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  line-height: 28px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/
.jp-DocumentSearch-input {
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  font-size: var(--jp-ui-font-size1);
  background-color: var(--jp-layout-color0);
  font-family: var(--jp-ui-font-family);
  padding: 2px 1px;
  resize: none;
}

.jp-DocumentSearch-overlay {
  position: absolute;
  background-color: var(--jp-toolbar-background);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  border-left: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  top: 0;
  right: 0;
  z-index: 7;
  min-width: 405px;
  padding: 2px;
  font-size: var(--jp-ui-font-size1);

  --jp-private-document-search-button-height: 20px;
}

.jp-DocumentSearch-overlay button {
  background-color: var(--jp-toolbar-background);
  outline: 0;
}

.jp-DocumentSearch-overlay button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-overlay button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-overlay-row {
  display: flex;
  align-items: center;
  margin-bottom: 2px;
}

.jp-DocumentSearch-button-content {
  display: inline-block;
  cursor: pointer;
  box-sizing: border-box;
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-button-content svg {
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-input-wrapper {
  border: var(--jp-border-width) solid var(--jp-border-color0);
  display: flex;
  background-color: var(--jp-layout-color0);
  margin: 2px;
}

.jp-DocumentSearch-input-wrapper:focus-within {
  border-color: var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper {
  all: initial;
  overflow: hidden;
  display: inline-block;
  border: none;
  box-sizing: border-box;
}

.jp-DocumentSearch-toggle-wrapper {
  width: 14px;
  height: 14px;
}

.jp-DocumentSearch-button-wrapper {
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
}

.jp-DocumentSearch-toggle-wrapper:focus,
.jp-DocumentSearch-button-wrapper:focus {
  outline: var(--jp-border-width) solid
    var(--jp-cell-editor-active-border-color);
  outline-offset: -1px;
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper,
.jp-DocumentSearch-button-content:focus {
  outline: none;
}

.jp-DocumentSearch-toggle-placeholder {
  width: 5px;
}

.jp-DocumentSearch-input-button::before {
  display: block;
  padding-top: 100%;
}

.jp-DocumentSearch-input-button-off {
  opacity: var(--jp-search-toggle-off-opacity);
}

.jp-DocumentSearch-input-button-off:hover {
  opacity: var(--jp-search-toggle-hover-opacity);
}

.jp-DocumentSearch-input-button-on {
  opacity: var(--jp-search-toggle-on-opacity);
}

.jp-DocumentSearch-index-counter {
  padding-left: 10px;
  padding-right: 10px;
  user-select: none;
  min-width: 35px;
  display: inline-block;
}

.jp-DocumentSearch-up-down-wrapper {
  display: inline-block;
  padding-right: 2px;
  margin-left: auto;
  white-space: nowrap;
}

.jp-DocumentSearch-spacer {
  margin-left: auto;
}

.jp-DocumentSearch-up-down-wrapper button {
  outline: 0;
  border: none;
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
  vertical-align: middle;
  margin: 1px 5px 2px;
}

.jp-DocumentSearch-up-down-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-up-down-button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-filter-button {
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-filter-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled:hover {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-search-options {
  padding: 0 8px;
  margin-left: 3px;
  width: 100%;
  display: grid;
  justify-content: start;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  justify-items: stretch;
}

.jp-DocumentSearch-search-filter-disabled {
  color: var(--jp-ui-font-color2);
}

.jp-DocumentSearch-search-filter {
  display: flex;
  align-items: center;
  user-select: none;
}

.jp-DocumentSearch-regex-error {
  color: var(--jp-error-color0);
}

.jp-DocumentSearch-replace-button-wrapper {
  overflow: hidden;
  display: inline-block;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color0);
  margin: auto 2px;
  padding: 1px 4px;
  height: calc(var(--jp-private-document-search-button-height) + 2px);
}

.jp-DocumentSearch-replace-button-wrapper:focus {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-replace-button {
  display: inline-block;
  text-align: center;
  cursor: pointer;
  box-sizing: border-box;
  color: var(--jp-ui-font-color1);

  /* height - 2 * (padding of wrapper) */
  line-height: calc(var(--jp-private-document-search-button-height) - 2px);
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-replace-button:focus {
  outline: none;
}

.jp-DocumentSearch-replace-wrapper-class {
  margin-left: 14px;
  display: flex;
}

.jp-DocumentSearch-replace-toggle {
  border: none;
  background-color: var(--jp-toolbar-background);
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-replace-toggle:hover {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.cm-editor {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;

  /* Changed to auto to autogrow */
}

.cm-editor pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .cm-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

.jp-CodeMirrorEditor {
  cursor: text;
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.cm-editor.jp-mod-readOnly .cm-cursor {
  display: none;
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.cm-searching,
.cm-searching span {
  /* `.cm-searching span`: we need to override syntax highlighting */
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.cm-searching::selection,
.cm-searching span::selection {
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.jp-current-match > .cm-searching,
.jp-current-match > .cm-searching span,
.cm-searching > .jp-current-match,
.cm-searching > .jp-current-match span {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.jp-current-match > .cm-searching::selection,
.cm-searching > .jp-current-match::selection,
.jp-current-match > .cm-searching span::selection {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.cm-trailingspace {
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAFCAYAAAB4ka1VAAAAsElEQVQIHQGlAFr/AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA7+r3zKmT0/+pk9P/7+r3zAAAAAAAAAAABAAAAAAAAAAA6OPzM+/q9wAAAAAA6OPzMwAAAAAAAAAAAgAAAAAAAAAAGR8NiRQaCgAZIA0AGR8NiQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQyoYJ/SY80UAAAAASUVORK5CYII=);
  background-position: center left;
  background-repeat: repeat-x;
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .cm-ySelectionCaret {
  position: relative;
  border-left: 1px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret > .cm-ySelectionInfo {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -1px;
  font-size: 0.95em;
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 101;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .cm-ySelectionInfo {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret:hover > .cm-ySelectionInfo {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser .jp-SidePanel-content {
  display: flex;
  flex-direction: column;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  flex-wrap: wrap;
  row-gap: 12px;
  border-bottom: none;
  height: auto;
  margin: 8px 12px 0;
  box-shadow: none;
  padding: 0;
  justify-content: flex-start;
}

.jp-FileBrowser-Panel {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0 2px;
  padding: 0 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0;
  padding-right: 2px;
  align-items: center;
  height: unset;
}

.jp-FileBrowser-toolbar > .jp-Toolbar-item .jp-ToolbarButtonComponent {
  width: 40px;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileSize-hidden {
  display: none;
}

.jp-FileBrowser .lm-AccordionPanel > h3:first-child {
  display: none;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  align-items: center;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-headerItem.jp-id-filesize {
  flex: 0 0 75px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-checkboxWrapper {
  /* Increases hit area of checkbox. */
  padding: 4px;
}

.jp-DirListing-header
  .jp-DirListing-checkboxWrapper
  + .jp-DirListing-headerItem {
  padding-left: 4px;
}

.jp-DirListing-content .jp-DirListing-checkboxWrapper {
  position: relative;
  left: -4px;
  margin: -4px 0 -4px -8px;
}

.jp-DirListing-checkboxWrapper.jp-mod-visible {
  visibility: visible;
}

/* For devices that support hovering, hide checkboxes until hovered, selected...
*/
@media (hover: hover) {
  .jp-DirListing-checkboxWrapper {
    visibility: hidden;
  }

  .jp-DirListing-item:hover .jp-DirListing-checkboxWrapper,
  .jp-DirListing-item.jp-mod-selected .jp-DirListing-checkboxWrapper {
    visibility: visible;
  }
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemText:focus {
  outline-width: 2px;
  outline-color: var(--jp-inverse-layout-color1);
  outline-style: solid;
  outline-offset: 1px;
}

.jp-DirListing-item.jp-mod-selected .jp-DirListing-itemText:focus {
  outline-color: var(--jp-layout-color1);
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-itemFileSize {
  flex: 0 0 90px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon::before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon::before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-OutputPrompt {
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-prompt {
  display: table-cell;
  vertical-align: top;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea .jp-RenderedText {
  padding-left: 1ch;
}

/**
 * Prompt overlay.
 */

.jp-OutputArea-promptOverlay {
  position: absolute;
  top: 0;
  width: var(--jp-cell-prompt-width);
  height: 100%;
  opacity: 0.5;
}

.jp-OutputArea-promptOverlay:hover {
  background: var(--jp-layout-color2);
  box-shadow: inset 0 0 1px var(--jp-inverse-layout-color0);
  cursor: zoom-out;
}

.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay:hover {
  cursor: zoom-in;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0;
  padding: 0;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

.jp-TrimmedOutputs pre {
  background: var(--jp-layout-color3);
  font-size: calc(var(--jp-code-font-size) * 1.4);
  text-align: center;
  text-transform: uppercase;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/* Hide empty lines in the output area, for instance due to cleared widgets */
.jp-OutputArea-prompt:empty {
  padding: 0;
  border: 0;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0;
  width: 100%;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;

  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;

  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0 0.25em;
  margin: 0 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input::placeholder {
  opacity: 0;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

.jp-Stdin-input:focus::placeholder {
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

@media print {
  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-OutputPrompt {
    display: table-row;
    text-align: left;
  }

  .jp-OutputArea-child .jp-OutputArea-output {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }
}

/* Trimmed outputs warning */
.jp-TrimmedOutputs > a {
  margin: 10px;
  text-decoration: none;
  cursor: pointer;
}

.jp-TrimmedOutputs > a:hover {
  text-decoration: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Table of Contents
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toc-active-width: 4px;
}

.jp-TableOfContents {
  display: flex;
  flex-direction: column;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  height: 100%;
}

.jp-TableOfContents-placeholder {
  text-align: center;
}

.jp-TableOfContents-placeholderContent {
  color: var(--jp-content-font-color2);
  padding: 8px;
}

.jp-TableOfContents-placeholderContent > h3 {
  margin-bottom: var(--jp-content-heading-margin-bottom);
}

.jp-TableOfContents .jp-SidePanel-content {
  overflow-y: auto;
}

.jp-TableOfContents-tree {
  margin: 4px;
}

.jp-TableOfContents ol {
  list-style-type: none;
}

/* stylelint-disable-next-line selector-max-type */
.jp-TableOfContents li > ol {
  /* Align left border with triangle icon center */
  padding-left: 11px;
}

.jp-TableOfContents-content {
  /* left margin for the active heading indicator */
  margin: 0 0 0 var(--jp-private-toc-active-width);
  padding: 0;
  background-color: var(--jp-layout-color1);
}

.jp-tocItem {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-tocItem-heading {
  display: flex;
  cursor: pointer;
}

.jp-tocItem-heading:hover {
  background-color: var(--jp-layout-color2);
}

.jp-tocItem-content {
  display: block;
  padding: 4px 0;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow-x: hidden;
}

.jp-tocItem-collapser {
  height: 20px;
  margin: 2px 2px 0;
  padding: 0;
  background: none;
  border: none;
  cursor: pointer;
}

.jp-tocItem-collapser:hover {
  background-color: var(--jp-layout-color3);
}

/* Active heading indicator */

.jp-tocItem-heading::before {
  content: ' ';
  background: transparent;
  width: var(--jp-private-toc-active-width);
  height: 24px;
  position: absolute;
  left: 0;
  border-radius: var(--jp-border-radius);
}

.jp-tocItem-heading.jp-tocItem-active::before {
  background-color: var(--jp-brand-color1);
}

.jp-tocItem-heading:hover.jp-tocItem-active::before {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;

  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Hiding collapsers in print mode.

Note: input and output wrappers have "display: block" propery in print mode.
*/

@media print {
  .jp-Collapser {
    display: none;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0;
  width: 100%;
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-InputArea-editor {
  display: table-cell;
  overflow: hidden;
  vertical-align: top;

  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  display: table-cell;
  vertical-align: top;
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-InputArea-editor {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }

  .jp-InputPrompt {
    display: table-row;
    text-align: left;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: table;
  table-layout: fixed;
  width: 100%;
}

.jp-Placeholder-prompt {
  display: table-cell;
  box-sizing: border-box;
}

.jp-Placeholder-content {
  display: table-cell;
  padding: 4px 6px;
  border: 1px solid transparent;
  border-radius: 0;
  background: none;
  box-sizing: border-box;
  cursor: pointer;
}

.jp-Placeholder-contentContainer {
  display: flex;
}

.jp-Placeholder-content:hover,
.jp-InputPlaceholder > .jp-Placeholder-content:hover {
  border-color: var(--jp-layout-color3);
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

.jp-PlaceholderText {
  white-space: nowrap;
  overflow-x: hidden;
  color: var(--jp-inverse-layout-color3);
  font-family: var(--jp-code-font-family);
}

.jp-InputPlaceholder > .jp-Placeholder-content {
  border-color: var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0;
  margin: 0;

  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 24em;
  margin-left: var(--jp-private-cell-scrolling-output-offset);
  resize: vertical;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea[style*='height'] {
  max-height: unset;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea::after {
  content: ' ';
  box-shadow: inset 0 0 6px 2px rgb(0 0 0 / 30%);
  width: 100%;
  height: 100%;
  position: sticky;
  bottom: 0;
  top: 0;
  margin-top: -50%;
  float: left;
  display: block;
  pointer-events: none;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-child {
  padding-top: 6px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay {
  left: calc(-1 * var(--jp-private-cell-scrolling-output-offset));
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  display: table-cell;
  width: 100%;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/* collapseHeadingButton (show always if hiddenCellsButton is _not_ shown) */
.jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  font-size: var(--jp-code-font-size);
  position: absolute;
  background-color: transparent;
  background-size: 25px;
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: top;
  background-image: var(--jp-icon-caret-down);
  right: 0;
  top: 0;
  bottom: 0;
}

.jp-collapseHeadingButton.jp-mod-collapsed {
  background-image: var(--jp-icon-caret-right);
}

/*
 set the container font size to match that of content
 so that the nested collapse buttons have the right size
*/
.jp-MarkdownCell .jp-InputPrompt {
  font-size: var(--jp-content-font-size1);
}

/*
  Align collapseHeadingButton with cell top header
  The font sizes are identical to the ones in packages/rendermime/style/base.css
*/
.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='1'] {
  font-size: var(--jp-content-font-size5);
  background-position-y: calc(0.3 * var(--jp-content-font-size5));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='2'] {
  font-size: var(--jp-content-font-size4);
  background-position-y: calc(0.3 * var(--jp-content-font-size4));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='3'] {
  font-size: var(--jp-content-font-size3);
  background-position-y: calc(0.3 * var(--jp-content-font-size3));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='4'] {
  font-size: var(--jp-content-font-size2);
  background-position-y: calc(0.3 * var(--jp-content-font-size2));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='5'] {
  font-size: var(--jp-content-font-size1);
  background-position-y: top;
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='6'] {
  font-size: var(--jp-content-font-size0);
  background-position-y: top;
}

/* collapseHeadingButton (show only on (hover,active) if hiddenCellsButton is shown) */
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-collapseHeadingButton {
  display: none;
}

.jp-Notebook.jp-mod-showHiddenCellsButton
  :is(.jp-MarkdownCell:hover, .jp-mod-active)
  .jp-collapseHeadingButton {
  display: flex;
}

/* showHiddenCellsButton (only show if jp-mod-showHiddenCellsButton is set, which
is a consequence of the showHiddenCellsButton option in Notebook Settings)*/
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
  display: flex;
}

.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-showHiddenCellsButton {
  display: none;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Using block instead of flex to allow the use of the break-inside CSS property for
cell outputs.
*/

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-notebook-toolbar-padding: 2px 5px 2px 2px;
}

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: var(--jp-notebook-toolbar-padding);

  /* disable paint containment from lumino 2.0 default strict CSS containment */
  contain: style size !important;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

.jp-Toolbar-responsive-popup {
  position: absolute;
  height: fit-content;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-end;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: var(--jp-notebook-toolbar-padding);
  z-index: 1;
  right: 0;
  top: 0;
}

.jp-Toolbar > .jp-Toolbar-responsive-opener {
  margin-left: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-Notebook-ExecutionIndicator {
  position: relative;
  display: inline-block;
  height: 100%;
  z-index: 9997;
}

.jp-Notebook-ExecutionIndicator-tooltip {
  visibility: hidden;
  height: auto;
  width: max-content;
  width: -moz-max-content;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color1);
  text-align: justify;
  border-radius: 6px;
  padding: 0 5px;
  position: fixed;
  display: table;
}

.jp-Notebook-ExecutionIndicator-tooltip.up {
  transform: translateX(-50%) translateY(-100%) translateY(-32px);
}

.jp-Notebook-ExecutionIndicator-tooltip.down {
  transform: translateX(calc(-100% + 16px)) translateY(5px);
}

.jp-Notebook-ExecutionIndicator-tooltip.hidden {
  display: none;
}

.jp-Notebook-ExecutionIndicator:hover .jp-Notebook-ExecutionIndicator-tooltip {
  visibility: visible;
}

.jp-Notebook-ExecutionIndicator span {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  color: var(--jp-ui-font-color1);
  line-height: 24px;
  display: block;
}

.jp-Notebook-ExecutionIndicator-progress-bar {
  display: flex;
  justify-content: center;
  height: 100%;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*
 * Execution indicator
 */
.jp-tocItem-content::after {
  content: '';

  /* Must be identical to form a circle */
  width: 12px;
  height: 12px;
  background: none;
  border: none;
  position: absolute;
  right: 0;
}

.jp-tocItem-content[data-running='0']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background: none;
}

.jp-tocItem-content[data-running='1']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background-color: var(--jp-inverse-layout-color3);
}

.jp-tocItem-content[data-running='0'],
.jp-tocItem-content[data-running='1'] {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Notebook-footer {
  height: 27px;
  margin-left: calc(
    var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
      var(--jp-cell-padding)
  );
  width: calc(
    100% -
      (
        var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
          var(--jp-cell-padding) + var(--jp-cell-padding)
      )
  );
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  color: var(--jp-ui-font-color3);
  margin-top: 6px;
  background: none;
  cursor: pointer;
}

.jp-Notebook-footer:focus {
  border-color: var(--jp-cell-editor-active-border-color);
}

/* For devices that support hovering, hide footer until hover */
@media (hover: hover) {
  .jp-Notebook-footer {
    opacity: 0;
  }

  .jp-Notebook-footer:focus,
  .jp-Notebook-footer:hover {
    opacity: 1;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-side-by-side-output-size: 1fr;
  --jp-side-by-side-resized-cell: var(--jp-side-by-side-output-size);
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

/* stylelint-disable selector-max-class */

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}

.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt::before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-ActiveCellTool {
  padding: 12px 0;
  display: flex;
}

.jp-ActiveCellTool-Content {
  flex: 1 1 auto;
}

.jp-ActiveCellTool .jp-ActiveCellTool-CellContent {
  background: var(--jp-cell-editor-background);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  min-height: 29px;
}

.jp-ActiveCellTool .jp-InputPrompt {
  min-width: calc(var(--jp-cell-prompt-width) * 0.75);
}

.jp-ActiveCellTool-CellContent > pre {
  padding: 5px 4px;
  margin: 0;
  white-space: normal;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label,
.jp-NumberSetter label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0;
}

.jp-NumberSetter input {
  width: 100%;
  margin-top: 4px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Side-by-side Mode (.jp-mod-sideBySide)
|----------------------------------------------------------------------------*/
.jp-mod-sideBySide.jp-Notebook .jp-Notebook-cell {
  margin-top: 3em;
  margin-bottom: 3em;
  margin-left: 5%;
  margin-right: 5%;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell {
  display: grid;
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-output-size)
    );
  grid-template-rows: auto minmax(0, 1fr) auto;
  grid-template-areas:
    'header header header'
    'input handle output'
    'footer footer footer';
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell.jp-mod-resizedCell {
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-resized-cell)
    );
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellHeader {
  grid-area: header;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-inputWrapper {
  grid-area: input;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-outputWrapper {
  /* overwrite the default margin (no vertical separation needed in side by side move */
  margin-top: 0;
  grid-area: output;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellFooter {
  grid-area: footer;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle {
  grid-area: handle;
  user-select: none;
  display: block;
  height: 100%;
  cursor: ew-resize;
  padding: 0 var(--jp-cell-padding);
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle::after {
  content: '';
  display: block;
  background: var(--jp-border-color2);
  height: 100%;
  width: 5px;
}

.jp-mod-sideBySide.jp-Notebook
  .jp-CodeCell.jp-mod-resizedCell
  .jp-CellResizeHandle::after {
  background: var(--jp-border-color0);
}

.jp-CellResizeHandle {
  display: none;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0 2px 1px -1px var(--jp-shadow-umbra-color),
    0 1px 1px 0 var(--jp-shadow-penumbra-color),
    0 1px 3px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0 3px 1px -2px var(--jp-shadow-umbra-color),
    0 2px 2px 0 var(--jp-shadow-penumbra-color),
    0 1px 5px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0 2px 4px -1px var(--jp-shadow-umbra-color),
    0 4px 5px 0 var(--jp-shadow-penumbra-color),
    0 1px 10px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0 3px 5px -1px var(--jp-shadow-umbra-color),
    0 6px 10px 0 var(--jp-shadow-penumbra-color),
    0 1px 18px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0 5px 5px -3px var(--jp-shadow-umbra-color),
    0 8px 10px 1px var(--jp-shadow-penumbra-color),
    0 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0 7px 8px -4px var(--jp-shadow-umbra-color),
    0 12px 17px 2px var(--jp-shadow-penumbra-color),
    0 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0 8px 10px -5px var(--jp-shadow-umbra-color),
    0 16px 24px 2px var(--jp-shadow-penumbra-color),
    0 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0 10px 13px -6px var(--jp-shadow-umbra-color),
    0 20px 31px 3px var(--jp-shadow-penumbra-color),
    0 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0 11px 15px -7px var(--jp-shadow-umbra-color),
    0 24px 38px 3px var(--jp-shadow-penumbra-color),
    0 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-inverse-border-color: var(--md-grey-600);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;
  --jp-ui-font-family: system-ui, -apple-system, blinkmacsystemfont, 'Segoe UI',
    helvetica, arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;
  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);
  --jp-content-link-color: var(--md-blue-900);
  --jp-content-font-family: system-ui, -apple-system, blinkmacsystemfont,
    'Segoe UI', helvetica, arial, sans-serif, 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: menlo, consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);
  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);
  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);
  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);
  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;
  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;
  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);
  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);

  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;

  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-inverse-border-color);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: rgb(0, 54, 109);
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #a2f;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #a2f;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /*
    RTC user specific colors.
    These colors are used for the cursor, username in the editor,
    and the icon of the user.
  */

  --jp-collaborator-color1: #ffad8e;
  --jp-collaborator-color2: #dac83d;
  --jp-collaborator-color3: #72dd76;
  --jp-collaborator-color4: #00e4d0;
  --jp-collaborator-color5: #45d4ff;
  --jp-collaborator-color6: #e2b1ff;
  --jp-collaborator-color7: #ff9de6;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);

  /* Button colors */
  --jp-accept-color-normal: var(--md-blue-700);
  --jp-accept-color-hover: var(--md-blue-800);
  --jp-accept-color-active: var(--md-blue-900);
  --jp-warn-color-normal: var(--md-red-700);
  --jp-warn-color-hover: var(--md-red-800);
  --jp-warn-color-active: var(--md-red-900);
  --jp-reject-color-normal: var(--md-grey-600);
  --jp-reject-color-hover: var(--md-grey-700);
  --jp-reject-color-active: var(--md-grey-800);

  /* File or activity icons and switch semantic variables */
  --jp-jupyter-icon-color: #f37626;
  --jp-notebook-icon-color: #f37626;
  --jp-json-icon-color: var(--md-orange-700);
  --jp-console-icon-background-color: var(--md-blue-700);
  --jp-console-icon-color: white;
  --jp-terminal-icon-background-color: var(--md-grey-800);
  --jp-terminal-icon-color: var(--md-grey-200);
  --jp-text-editor-icon-color: var(--md-grey-700);
  --jp-inspector-icon-color: var(--md-grey-700);
  --jp-switch-color: var(--md-grey-400);
  --jp-switch-true-position-color: var(--md-orange-900);
}
</style>
<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.cm-editor.cm-s-jupyter .highlight pre {
/* weird, but --jp-code-padding defined to be 5px but 4px horizontal padding is hardcoded for pre.cm-line */
  padding: var(--jp-code-padding) 4px;
  margin: 0;

  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;

}

.jp-OutputArea-output pre {
  line-height: inherit;
  font-family: inherit;
}

.jp-RenderedText pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@page {
    margin: 0.5in; /* Margin for each printed piece of paper */
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}
</style>
<!-- Load mathjax -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
<!-- MathJax configuration -->
<script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                messageStyle: 'none',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
<!-- End of mathjax configuration --><script type="module">
  document.addEventListener("DOMContentLoaded", async () => {
    const diagrams = document.querySelectorAll(".jp-Mermaid > pre.mermaid");
    // do not load mermaidjs if not needed
    if (!diagrams.length) {
      return;
    }
    const mermaid = (await import("https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.7.0/mermaid.esm.min.mjs")).default;
    const parser = new DOMParser();

    mermaid.initialize({
      maxTextSize: 100000,
      maxEdges: 100000,
      startOnLoad: false,
      fontFamily: window
        .getComputedStyle(document.body)
        .getPropertyValue("--jp-ui-font-family"),
      theme: document.querySelector("body[data-jp-theme-light='true']")
        ? "default"
        : "dark",
    });

    let _nextMermaidId = 0;

    function makeMermaidImage(svg) {
      const img = document.createElement("img");
      const doc = parser.parseFromString(svg, "image/svg+xml");
      const svgEl = doc.querySelector("svg");
      const { maxWidth } = svgEl?.style || {};
      const firstTitle = doc.querySelector("title");
      const firstDesc = doc.querySelector("desc");

      img.setAttribute("src", `data:image/svg+xml,${encodeURIComponent(svg)}`);
      if (maxWidth) {
        img.width = parseInt(maxWidth);
      }
      if (firstTitle) {
        img.setAttribute("alt", firstTitle.textContent);
      }
      if (firstDesc) {
        const caption = document.createElement("figcaption");
        caption.className = "sr-only";
        caption.textContent = firstDesc.textContent;
        return [img, caption];
      }
      return [img];
    }

    async function makeMermaidError(text) {
      let errorMessage = "";
      try {
        await mermaid.parse(text);
      } catch (err) {
        errorMessage = `${err}`;
      }

      const result = document.createElement("details");
      result.className = 'jp-RenderedMermaid-Details';
      const summary = document.createElement("summary");
      summary.className = 'jp-RenderedMermaid-Summary';
      const pre = document.createElement("pre");
      const code = document.createElement("code");
      code.innerText = text;
      pre.appendChild(code);
      summary.appendChild(pre);
      result.appendChild(summary);

      const warning = document.createElement("pre");
      warning.innerText = errorMessage;
      result.appendChild(warning);
      return [result];
    }

    async function renderOneMarmaid(src) {
      const id = `jp-mermaid-${_nextMermaidId++}`;
      const parent = src.parentNode;
      let raw = src.textContent.trim();
      const el = document.createElement("div");
      el.style.visibility = "hidden";
      document.body.appendChild(el);
      let results = null;
      let output = null;
      try {
        let { svg } = await mermaid.render(id, raw, el);
        svg = cleanMermaidSvg(svg);
        results = makeMermaidImage(svg);
        output = document.createElement("figure");
        results.map(output.appendChild, output);
      } catch (err) {
        parent.classList.add("jp-mod-warning");
        results = await makeMermaidError(raw);
        output = results[0];
      } finally {
        el.remove();
      }
      parent.classList.add("jp-RenderedMermaid");
      parent.appendChild(output);
    }


    /**
     * Post-process to ensure mermaid diagrams contain only valid SVG and XHTML.
     */
    function cleanMermaidSvg(svg) {
      return svg.replace(RE_VOID_ELEMENT, replaceVoidElement);
    }


    /**
     * A regular expression for all void elements, which may include attributes and
     * a slash.
     *
     * @see https://developer.mozilla.org/en-US/docs/Glossary/Void_element
     *
     * Of these, only `<br>` is generated by Mermaid in place of `\n`,
     * but _any_ "malformed" tag will break the SVG rendering entirely.
     */
    const RE_VOID_ELEMENT =
      /<\s*(area|base|br|col|embed|hr|img|input|link|meta|param|source|track|wbr)\s*([^>]*?)\s*>/gi;

    /**
     * Ensure a void element is closed with a slash, preserving any attributes.
     */
    function replaceVoidElement(match, tag, rest) {
      rest = rest.trim();
      if (!rest.endsWith('/')) {
        rest = `${rest} /`;
      }
      return `<${tag} ${rest}>`;
    }

    void Promise.all([...diagrams].map(renderOneMarmaid));
  });
</script>
<style>
  .jp-Mermaid:not(.jp-RenderedMermaid) {
    display: none;
  }

  .jp-RenderedMermaid {
    overflow: auto;
    display: flex;
  }

  .jp-RenderedMermaid.jp-mod-warning {
    width: auto;
    padding: 0.5em;
    margin-top: 0.5em;
    border: var(--jp-border-width) solid var(--jp-warn-color2);
    border-radius: var(--jp-border-radius);
    color: var(--jp-ui-font-color1);
    font-size: var(--jp-ui-font-size1);
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .jp-RenderedMermaid figure {
    margin: 0;
    overflow: auto;
    max-width: 100%;
  }

  .jp-RenderedMermaid img {
    max-width: 100%;
  }

  .jp-RenderedMermaid-Details > pre {
    margin-top: 1em;
  }

  .jp-RenderedMermaid-Summary {
    color: var(--jp-warn-color2);
  }

  .jp-RenderedMermaid:not(.jp-mod-warning) pre {
    display: none;
  }

  .jp-RenderedMermaid-Summary > pre {
    display: inline-block;
    white-space: normal;
  }
</style>
<!-- End of mermaid configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">
<main><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=b105073a-92d8-4a01-98ab-f91b4f1c5c7a">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="kn">import</span><span class="w"> </span><span class="nn">pandas</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">pd</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">numpy</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">np</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">matplotlib.pyplot</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">plt</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=bb0d9613-1d39-4e2b-a6cb-76f76fd9bd47">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">"video_games_sales.csv"</span><span class="p">)</span> 
<span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[2]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>Rank</th>
<th>Name</th>
<th>Platform</th>
<th>Year</th>
<th>Genre</th>
<th>Publisher</th>
<th>NA_Sales</th>
<th>EU_Sales</th>
<th>JP_Sales</th>
<th>Other_Sales</th>
<th>Global_Sales</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>1</td>
<td>Wii Sports</td>
<td>Wii</td>
<td>2006.0</td>
<td>Sports</td>
<td>Nintendo</td>
<td>41.49</td>
<td>29.02</td>
<td>3.77</td>
<td>8.46</td>
<td>82.74</td>
</tr>
<tr>
<th>1</th>
<td>2</td>
<td>Super Mario Bros.</td>
<td>NES</td>
<td>1985.0</td>
<td>Platform</td>
<td>Nintendo</td>
<td>29.08</td>
<td>3.58</td>
<td>6.81</td>
<td>0.77</td>
<td>40.24</td>
</tr>
<tr>
<th>2</th>
<td>3</td>
<td>Mario Kart Wii</td>
<td>Wii</td>
<td>2008.0</td>
<td>Racing</td>
<td>Nintendo</td>
<td>15.85</td>
<td>12.88</td>
<td>3.79</td>
<td>3.31</td>
<td>35.82</td>
</tr>
<tr>
<th>3</th>
<td>4</td>
<td>Wii Sports Resort</td>
<td>Wii</td>
<td>2009.0</td>
<td>Sports</td>
<td>Nintendo</td>
<td>15.75</td>
<td>11.01</td>
<td>3.28</td>
<td>2.96</td>
<td>33.00</td>
</tr>
<tr>
<th>4</th>
<td>5</td>
<td>Pokemon Red/Pokemon Blue</td>
<td>GB</td>
<td>1996.0</td>
<td>Role-Playing</td>
<td>Nintendo</td>
<td>11.27</td>
<td>8.89</td>
<td>10.22</td>
<td>1.00</td>
<td>31.37</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=e6aeb951-5861-4bf2-9e3b-01fa4636a415">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="n">df</span><span class="o">.</span><span class="n">shape</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">df</span><span class="o">.</span><span class="n">columns</span><span class="p">)</span>
<span class="n">df</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain" tabindex="0">
<pre>(16598, 11)
Index(['Rank', 'Name', 'Platform', 'Year', 'Genre', 'Publisher', 'NA_Sales',
       'EU_Sales', 'JP_Sales', 'Other_Sales', 'Global_Sales'],
      dtype='object')
&lt;class 'pandas.core.frame.DataFrame'&gt;
RangeIndex: 16598 entries, 0 to 16597
Data columns (total 11 columns):
 #   Column        Non-Null Count  Dtype  
---  ------        --------------  -----  
 0   Rank          16598 non-null  int64  
 1   Name          16598 non-null  object 
 2   Platform      16598 non-null  object 
 3   Year          16327 non-null  float64
 4   Genre         16598 non-null  object 
 5   Publisher     16540 non-null  object 
 6   NA_Sales      16598 non-null  float64
 7   EU_Sales      16598 non-null  float64
 8   JP_Sales      16598 non-null  float64
 9   Other_Sales   16598 non-null  float64
 10  Global_Sales  16598 non-null  float64
dtypes: float64(6), int64(1), object(4)
memory usage: 1.4+ MB
</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=d009d1ef-1cb3-4b96-b596-918fe5d377b6">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">columns</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">columns</span><span class="o">.</span><span class="n">str</span><span class="o">.</span><span class="n">strip</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=e5471e75-e837-4cbf-8d50-4824bca731c4">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">]</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_numeric</span><span class="p">(</span><span class="n">df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">],</span> <span class="n">errors</span><span class="o">=</span><span class="s1">'coerce'</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">dropna</span><span class="p">(</span><span class="n">subset</span><span class="o">=</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">])</span>
<span class="n">df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">]</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">]</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="nb">int</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=681abfb1-0736-436b-8f65-69b34ddd200d">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="s1">'Decade'</span><span class="p">]</span> <span class="o">=</span> <span class="p">(</span><span class="n">df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">]</span> <span class="o">//</span> <span class="mi">10</span><span class="p">)</span> <span class="o">*</span> <span class="mi">10</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=f4106a7c-f371-48d7-a4a5-b60607f3179e">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="k">def</span><span class="w"> </span><span class="nf">platform_group</span><span class="p">(</span><span class="n">platform</span><span class="p">):</span>
    <span class="n">p</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="n">platform</span><span class="p">)</span><span class="o">.</span><span class="n">lower</span><span class="p">()</span>

    <span class="c1"># Nintendo</span>
    <span class="k">if</span> <span class="nb">any</span><span class="p">(</span><span class="n">x</span> <span class="ow">in</span> <span class="n">p</span> <span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="p">[</span><span class="s1">'nintendo'</span><span class="p">,</span> <span class="s1">'wii'</span><span class="p">,</span> <span class="s1">'switch'</span><span class="p">,</span> <span class="s1">'ds'</span><span class="p">,</span> <span class="s1">'3ds'</span><span class="p">,</span> <span class="s1">'gameboy'</span><span class="p">,</span> <span class="s1">'gba'</span><span class="p">,</span> <span class="s1">'nes'</span><span class="p">,</span> <span class="s1">'snes'</span><span class="p">]):</span>
        <span class="k">return</span> <span class="s1">'Nintendo'</span>

    <span class="c1"># Sony </span>
    <span class="k">elif</span> <span class="s1">'ps1'</span> <span class="ow">in</span> <span class="n">p</span> <span class="ow">or</span> <span class="s1">'playstation 1'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'PS1'</span>
    <span class="k">elif</span> <span class="s1">'ps2'</span> <span class="ow">in</span> <span class="n">p</span> <span class="ow">or</span> <span class="s1">'playstation 2'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'PS2'</span>
    <span class="k">elif</span> <span class="s1">'ps3'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'PS3'</span>
    <span class="k">elif</span> <span class="s1">'ps4'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'PS4'</span>
    <span class="k">elif</span> <span class="s1">'psp'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'PSP'</span>
    <span class="k">elif</span> <span class="s1">'vita'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'PS Vita'</span>

    <span class="c1"># fallback Sony group</span>
    <span class="k">elif</span> <span class="s1">'playstation'</span> <span class="ow">in</span> <span class="n">p</span> <span class="ow">or</span> <span class="s1">'ps'</span> <span class="ow">in</span> <span class="n">p</span><span class="p">:</span>
        <span class="k">return</span> <span class="s1">'Sony (Other)'</span>

    <span class="k">else</span><span class="p">:</span>
        <span class="k">return</span> <span class="kc">None</span>

<span class="n">df</span><span class="p">[</span><span class="s1">'Platform_Type'</span><span class="p">]</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">'Platform'</span><span class="p">]</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="n">platform_group</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">dropna</span><span class="p">(</span><span class="n">subset</span><span class="o">=</span><span class="p">[</span><span class="s1">'Platform_Type'</span><span class="p">])</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=928645ab-a38c-4f6d-9ea4-c1a64b067b36">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [8]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">decade_sales</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">'Decade'</span><span class="p">)[</span><span class="s1">'Global_Sales'</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">reindex</span><span class="p">(</span>
    <span class="p">[</span><span class="mi">1980</span><span class="p">,</span> <span class="mi">1990</span><span class="p">,</span> <span class="mi">2000</span><span class="p">,</span> <span class="mi">2010</span><span class="p">,</span> <span class="mi">2020</span><span class="p">],</span>
    <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span>
<span class="p">)</span>

<span class="n">labels</span> <span class="o">=</span> <span class="p">[</span><span class="sa">f</span><span class="s2">"</span><span class="si">{</span><span class="n">d</span><span class="si">}</span><span class="s2">'s"</span> <span class="k">for</span> <span class="n">d</span> <span class="ow">in</span> <span class="n">decade_sales</span><span class="o">.</span><span class="n">index</span><span class="p">]</span>

<span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">labels</span><span class="p">,</span> <span class="n">decade_sales</span><span class="o">.</span><span class="n">values</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">"Video Game Sales by Decade"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">"Decade"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">"Global Sales (Millions)"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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IiIiojpmUCBauXJlbfdBREREZDRPfGPGGzduICMjAwqFAq1bt4aDg0NN9kVERERUZ6p9UnVhYSHee+89ODs747XXXkPXrl3h4uKCESNG4O7du7XRIxEREVGtqnYgmjBhAvbt24etW7ciPz8f+fn5+PXXX7Fv3z5ERUXVRo9EREREtarah8w2btyIn3/+Gd27d5emvf7667C0tMTgwYOxdOnSmuyPiIiIqNZVew/R3bt34eTkVGG6o6MjD5kRERFRg1TtQOTv74+ZM2fi3r170rSioiLMmjVLerYZERERUUNS7UNmS5YsQWBgoHRjRoVCgbS0NFhYWGDnzp210SMRERFRrap2IPL29sb58+exdu1anD17FkIIDB06FG+//TYsLS1ro0ciIiKiWvVE9yGytLRERERETfdCREREZBQGBaItW7YYvMCQkJAnboaIiIjIGAwKRG+++aZBC1MoFCgtLX2afoiIiIjqnEGBqKysrLb7ICIiIjKaal92T0RERPSsMfik6qKiIuzevRvBwcEAgKlTp0Kn00nzTUxMMHv2bFhYWNR8l0RERES1yOBAtHr1avz2229SIIqNjcWLL74oXWp/9uxZuLi4YPz48bXTKREREVEtMfiQ2bp16/Dee+/pTVu/fj327t2LvXv34osvvsBPP/1U4w0SERER1TaDA9G5c+fQunVr6b2FhQUaNfrvx1955RWcPn26ZrsjIiIiqgMGHzLTarUwNf1v+Y0bN/Tml5WV6Z1TRERERNRQGLyHyNXVFSdPnqxy/okTJ+Dq6lojTRERERHVJYMD0euvv47PPvtM7yn35cqfdt+vX78abY6IiIioLhh8yGzatGn46aef4OXlhTFjxqB169ZQKBQ4e/YsYmNjUVJSgmnTptVmr0RERES1wuBA5OTkhKSkJHz44YeYMmUKhBAAHjyuo0+fPvjmm2/g5ORUa40SERER1ZZqPe3e09MT8fHxuHXrFi5cuAAAaNmyJWxtbWulOSIiIqK6UK1AVM7W1havvPJKTfdCREREZBR8lhkRERHJHgMRERERyR4DEREREckeAxERERHJnlED0f79+9G/f3+4uLhAoVBg8+bNevOFEIiOjoaLiwssLS3RvXt3nDp1Sq9Gp9Nh7NixsLe3h5WVFUJCQnD16lW9mry8PISHh0OlUkGlUiE8PBz5+fm1vHVERETUUBg1EBUWFqJ9+/aIjY2tdP6CBQuwcOFCxMbG4vDhw1Cr1ejTpw9u374t1URGRmLTpk2Ii4vDgQMHcOfOHQQHB6O0tFSqCQsLQ1paGuLj4xEfH4+0tDSEh4fX+vYRERFRw/BEl93XlKCgIAQFBVU6TwiBxYsXY/r06QgNDQUA/Pvf/4aTkxPWr1+PUaNGQavV4ocffsCaNWvQu3dvAMDatWvh5uaGXbt2oW/fvjhz5gzi4+ORkpICX19fAMDy5cvh7++PjIwMeHl51c3GEhERUb1Vb88hyszMhEajQUBAgDRNqVSiW7duSEpKAgCkpqbi/v37ejUuLi7w9vaWapKTk6FSqaQwBAB+fn5QqVRSDREREcmbUfcQPYpGowGACo8DcXJywuXLl6Uac3NzNGvWrEJN+ec1Gg0cHR0rLN/R0VGqqYxOp4NOp5PeFxQUPNmGEBERUb1Xb/cQlVMoFHrvhRAVpj3s4ZrK6h+3nJiYGOkkbJVKBTc3t2p2TkRERA1FvQ1EarUaACrsxcnJyZH2GqnVahQXFyMvL++RNdevX6+w/Bs3bjzyYbRTp06FVquVXllZWU+1PURERFR/1dtA5OnpCbVajYSEBGlacXEx9u3bhy5dugAAOnXqBDMzM72a7OxsnDx5Uqrx9/eHVqvFoUOHpJqDBw9Cq9VKNZVRKpWwsbHRexEREdGzyajnEN25cwcXLlyQ3mdmZiItLQ22trZo0aIFIiMjMXfuXLRq1QqtWrXC3Llz0bhxY4SFhQEAVCoVRowYgaioKNjZ2cHW1hYTJ05Eu3btpKvO2rRpg8DAQERERGDZsmUAgJEjRyI4OJhXmBEREREAIweiI0eOoEePHtL7CRMmAACGDRuGVatWYdKkSSgqKsJHH32EvLw8+Pr64vfff4e1tbX0mUWLFsHU1BSDBw9GUVERevXqhVWrVsHExESqWbduHcaNGyddjRYSElLlvY+IiIhIfhRCCGHsJhqCgoICqFQqaLVaHj4jegoeU7YZu4UG49K8fjW2LI674Wpy3Mn4DP39XW/PISIiIiKqKwxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7Rn3aPZEx8WGXhuPDLonoWcc9RERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR79ToQRUdHQ6FQ6L3UarU0XwiB6OhouLi4wNLSEt27d8epU6f0lqHT6TB27FjY29vDysoKISEhuHr1al1vChEREdVj9ToQAcCLL76I7Oxs6ZWeni7NW7BgARYuXIjY2FgcPnwYarUaffr0we3bt6WayMhIbNq0CXFxcThw4ADu3LmD4OBglJaWGmNziIiIqB4yNXYDj2Nqaqq3V6icEAKLFy/G9OnTERoaCgD497//DScnJ6xfvx6jRo2CVqvFDz/8gDVr1qB3794AgLVr18LNzQ27du1C375963RbiIiIqH6q93uIzp8/DxcXF3h6emLo0KG4ePEiACAzMxMajQYBAQFSrVKpRLdu3ZCUlAQASE1Nxf379/VqXFxc4O3tLdVURafToaCgQO9FREREz6Z6HYh8fX2xevVq7Ny5E8uXL4dGo0GXLl2Qm5sLjUYDAHByctL7jJOTkzRPo9HA3NwczZo1q7KmKjExMVCpVNLLzc2tBreMiIiI6pN6HYiCgoIwcOBAtGvXDr1798a2bdsAPDg0Vk6hUOh9RghRYdrDDKmZOnUqtFqt9MrKynrCrSAiIqL6rl4HoodZWVmhXbt2OH/+vHRe0cN7enJycqS9Rmq1GsXFxcjLy6uypipKpRI2NjZ6LyIiIno2NahApNPpcObMGTg7O8PT0xNqtRoJCQnS/OLiYuzbtw9dunQBAHTq1AlmZmZ6NdnZ2Th58qRUQ0RERFSvrzKbOHEi+vfvjxYtWiAnJwdz5sxBQUEBhg0bBoVCgcjISMydOxetWrVCq1atMHfuXDRu3BhhYWEAAJVKhREjRiAqKgp2dnawtbXFxIkTpUNwREREREA9D0RXr17FW2+9hZs3b8LBwQF+fn5ISUmBu7s7AGDSpEkoKirCRx99hLy8PPj6+uL333+HtbW1tIxFixbB1NQUgwcPRlFREXr16oVVq1bBxMTEWJtFRERE9Uy9DkRxcXGPnK9QKBAdHY3o6OgqaywsLPD111/j66+/ruHuiIiI6FnRoM4hIiIiIqoNDEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQkewxEREREJHsMRERERCR7DEREREQke6bGboAAjynbjN1Cg3FpXj9jt0BERM8g7iEiIiIi2WMgIiIiItljICIiIiLZYyAiIiIi2WMgIiIiItljICIiIiLZYyAiIiIi2WMgIiIiItljICIiIiLZYyAiIiIi2WMgIiIiItljICIiIiLZYyAiIiIi2WMgIiIiItljICIiIiLZYyAiIiIi2ZNVIPrmm2/g6ekJCwsLdOrUCf/3f/9n7JaIiIioHpBNINqwYQMiIyMxffp0HDt2DF27dkVQUBCuXLli7NaIiIjIyGQTiBYuXIgRI0bg/fffR5s2bbB48WK4ublh6dKlxm6NiIiIjEwWgai4uBipqakICAjQmx4QEICkpCQjdUVERET1hamxG6gLN2/eRGlpKZycnPSmOzk5QaPRVPoZnU4HnU4nvddqtQCAgoKCGu+vTHe3xpf5rKrJ8ee4G47jbhwcd+OojX/nyXjKv08hxCPrZBGIyikUCr33QogK08rFxMRg1qxZFaa7ubnVSm9kGNViY3cgTxx34+C4GwfH/dl0+/ZtqFSqKufLIhDZ29vDxMSkwt6gnJycCnuNyk2dOhUTJkyQ3peVleHWrVuws7OrMkQ9SwoKCuDm5oasrCzY2NgYux3Z4LgbB8fdODjuxiG3cRdC4Pbt23BxcXlknSwCkbm5OTp16oSEhAQMGDBAmp6QkIA33nij0s8olUoolUq9aU2bNq3NNuslGxsbWfyFqW847sbBcTcOjrtxyGncH7VnqJwsAhEATJgwAeHh4ejcuTP8/f3x3Xff4cqVK/jggw+M3RoREREZmWwC0ZAhQ5Cbm4t//OMfyM7Ohre3N7Zv3w53d3djt0ZERERGJptABAAfffQRPvroI2O30SAolUrMnDmzwmFDql0cd+PguBsHx904OO6VU4jHXYdGRERE9IyTxY0ZiYiIiB6FgYiIiIhkj4GIiIiIZI+BiIiIiGSPgegZsH//fvTv3x8uLi5QKBTYvHmz3vzr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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=81dc5b75-b5c6-4632-9277-e62156f74d94">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [9]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="s1">'Company'</span><span class="p">]</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">'Platform_Type'</span><span class="p">]</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="k">lambda</span> <span class="n">x</span><span class="p">:</span> <span class="s1">'Nintendo'</span> <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="s1">'Nintendo'</span> <span class="k">else</span> <span class="s1">'Sony'</span><span class="p">)</span>

<span class="n">company_sales</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">'Company'</span><span class="p">)[</span><span class="s1">'Global_Sales'</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>

<span class="n">company_sales</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s1">'bar'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">"Nintendo vs Sony Total Sales"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">rotation</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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vr6+uu+++/Tiiy8qIyND33zzjaKiovTKK69oz549kqT33ntPAwYM0M0336wVK1Zo69at2rFjhx577DErVF7I4cOH9eWXX5Z7nfv5+ckYY73Wu3btqjVr1uj06dN6+OGH1ahRI0VHR+utt96q1LhQM/F0EmoUh8OhmTNnqmfPnnr99dev234bNmyowMBApaWlnXe5n59fhbcZGBiovLy8cu3ntp39Y56bm1vukd8ff/xRDRs2vOS+Hn30UY0cOVLZ2dn67rvvlJubq0cffdStJiIiQosWLZIkff311/r73/+uqVOn6tSpU3rttdcqNLa6detq0qRJWr16tXbv3m2N4/Tp0zpy5IhbkDHGKC8vz/qffUUNHjxYEydO1CuvvKLOnTsrLy9Po0aNqtS2zroax3zVqlXy8vLSunXrVLt2bat9zZo1V9S3czVu3FgjRoxQcnKy9uzZo1atWmnFihVq2rSpVq9e7XajcUlJySW317BhQ/n6+p73RvSzy8/q16+f+vXrp5KSEmVmZiolJUWDBw9WkyZNFBsbe+WDQ7XHmRjUOPHx8erZs6eef/55nThx4qpu+3z/05ekPn366OjRoyorK1PHjh3LTZGRkRXe11133aWPPvpIhw8fttrKysrcLvtIUvfu3SVJK1ascGvfsWOHsrOz1aNHj0vu69e//rVq166tJUuWaMmSJbr55putswTn06JFCz3zzDNq3bq1Pvvss4tuOzc397ztZy9bhIWFSZLVz3PH8e677+rkyZOXNY7zqV27tkaMGKGlS5dq9uzZateune68885KbeusihzzC71mHA6HPD095eHhYbUVFxdf1mcdnc/x48cv+Ho/91g7HA55e3u7BZi8vLzLejqpT58++vbbbxUYGHje13qTJk3KrePj46Nu3bpp5syZkqTPP/+8osNDDcWZGNRIM2fOVIcOHZSfn69WrVpdte22bt1a7733nubPn68OHTqoVq1a6tixowYNGqSVK1fq7rvv1pNPPqk77rhDXl5eOnTokDZt2qR+/fpV+IPGnnnmGa1du1bdu3fXc889pzp16uiVV14p9xhrZGSkRowYoZdfflm1atVSYmKiDhw4oGeffVbh4eH63e9+d8l91a9fX/fff7+WLFmiwsJCTZgwwe2R3C+//FKjR4/WQw89pObNm8vb21sbN27Ul19+eckPq2vVqpV69OihxMRE3XLLLfr555+1bds2/eUvf1FwcLCGDRsmSerZs6cSEhI0ceJEFRUV6c4779SXX36pKVOm6Pbbb1dSUlKFjt8vjRw5UrNmzdLOnTv1t7/9rdLbOasix/xCr5l77rlHs2fP1uDBgzVixAgdPXpUf/7zn63LmBW1d+9eJSQkaNCgQerWrZtCQ0NVUFCg9evX6/XXX1dcXJy6dOki6X9B5L333tPIkSP14IMPKicnR3/84x8VGhqqffv2XXQ/ycnJevfdd9W1a1f97ne/U5s2bXTmzBkdPHhQGzZs0Pjx4xUTE6PnnntOhw4dUo8ePdSoUSMVFhbqpZdekpeXl7p161apMaIGquo7i4Fr6XyPvp41ePBgI+myn056++233er2799vJJnFixdbbceOHTMPPvigqV+/vnE4HOaXb7HS0lLz5z//2bRt29bUrl3b1KtXz9x2223m8ccfN/v27XPb/z333FOuv+d7AuWTTz4xnTt3Nj4+PiYkJMT8/ve/N6+//nq5R6zLysrMzJkzTYsWLYyXl5dp2LCh+b//+z+Tk5NzscPnZsOGDdZTLV9//bXbssOHD5uhQ4ea2267zdStW9fUq1fPtGnTxsyZM+eCj0yftWDBAvPAAw+YZs2amTp16hhvb29zyy23mN/+9rfl+ldcXGwmTpxoIiIijJeXlwkNDTVPPPGEKSgocKuryDE8Ky4uzgQEBLg97n65zvc6u9xjfrHXzBtvvGEiIyONj4+PadasmUlJSTGLFi0q9+97OU8nFRQUmBdeeMF0797d3Hzzzcbb29vUrVvXtGvXzrzwwgvlxj1jxgzTpEkT4+PjY1q2bGkWLlxopkyZYs79s3Hu+8WY/z3O/cwzz5jIyEjj7e1tnE6nad26tfnd735nPU23bt06k5iYaPUlKCjI3H333ebf//73pQ43YHEYU4lPTQKAaiQ/P18REREaM2aMZs2aVdXdAXCZuJwEoMY6dOiQvvvuO7344ouqVauWnnzyyaruEoAK4MZeADXW3/72N8XFxWnPnj1auXKlbr755qruEoAK4HISAACwJc7EAAAAWyLEAAAAWyLEAAAAW6q2TyedOXNGP/74o/z8/Nw+dRIAANy4jDE6fvy4wsLC3D5U83yqbYj58ccfFR4eXtXdAAAAlZCTk1Puu8fOVW1DzNkv1MvJyZG/v38V9wYAAFyOoqIihYeHX9YX41bbEHP2EpK/vz8hBgAAm7mcW0G4sRcAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANgSIQYAANiSZ0WK58+fr/nz5+vAgQOSpFatWum5555TYmKiJGno0KFaunSp2zoxMTHKzMy05ktKSjRhwgS99dZbKi4uVo8ePfTqq6+qUaNGVk1BQYHGjh2rtWvXSpL69u2rl19+WfXr16/MGAGg2mjyh/VV3QVcRwdm3FPVXbihVehMTKNGjTRjxgx9+umn+vTTT9W9e3f169dPe/bssWp69+6t3Nxca3r//ffdtpGcnKzU1FStWrVKmzdv1okTJ9SnTx+VlZVZNYMHD1ZWVpbS0tKUlpamrKwsJSUlXeFQAQBAdVKhMzH33nuv2/yf/vQnzZ8/X5mZmWrVqpUkycfHRyEhIedd3+VyadGiRVq+fLni4+MlSStWrFB4eLg+/PBDJSQkKDs7W2lpacrMzFRMTIwkaeHChYqNjdXevXsVGRlZ4UECAIDqp9L3xJSVlWnVqlU6efKkYmNjrfaPP/5YQUFBatGihYYPH678/Hxr2c6dO1VaWqpevXpZbWFhYYqOjtaWLVskSVu3bpXT6bQCjCR17txZTqfTqjmfkpISFRUVuU0AAKD6qnCI2bVrl+rVqycfHx/99re/VWpqqqKioiRJiYmJWrlypTZu3Ki//OUv2rFjh7p3766SkhJJUl5enry9vdWgQQO3bQYHBysvL8+qCQoKKrffoKAgq+Z8UlJS5HQ6rSk8PLyiQwMAADZSoctJkhQZGamsrCwVFhbq3Xff1SOPPKKMjAxFRUVp4MCBVl10dLQ6duyoiIgIrV+/Xg888MAFt2mMkcPhsOZ/+fOFas41adIkjRs3zpovKioiyAAAUI1VOMR4e3vr1ltvlSR17NhRO3bs0EsvvaQFCxaUqw0NDVVERIT27dsnSQoJCdGpU6dUUFDgdjYmPz9fXbp0sWoOHz5cbltHjhxRcHDwBfvl4+MjHx+fig4HAADY1BV/TowxxrpcdK6jR48qJydHoaGhkqQOHTrIy8tL6enpVk1ubq52795thZjY2Fi5XC5t377dqtm2bZtcLpdVAwAAUKEzMU8//bQSExMVHh6u48ePa9WqVfr444+VlpamEydOaOrUqerfv79CQ0N14MABPf3002rYsKHuv/9+SZLT6dSwYcM0fvx4BQYGKiAgQBMmTFDr1q2tp5Vatmyp3r17a/jw4dbZnREjRqhPnz48mQQAACwVCjGHDx9WUlKScnNz5XQ61aZNG6Wlpalnz54qLi7Wrl27tGzZMhUWFio0NFR33XWXVq9eLT8/P2sbc+bMkaenpwYMGGB92N2SJUvk4eFh1axcuVJjx461nmLq27ev5s2bd5WGDAAAqgOHMcZUdSeuhaKiIjmdTrlcLvn7+1d1dwDgquATe2uWmviJvRX5+813JwEAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFsixAAAAFuqUIiZP3++2rRpI39/f/n7+ys2Nlb//Oc/reXGGE2dOlVhYWHy9fVVXFyc9uzZ47aNkpISjRkzRg0bNlTdunXVt29fHTp0yK2moKBASUlJcjqdcjqdSkpKUmFhYeVHCQAAqp0KhZhGjRppxowZ+vTTT/Xpp5+qe/fu6tevnxVUZs2apdmzZ2vevHnasWOHQkJC1LNnTx0/ftzaRnJyslJTU7Vq1Spt3rxZJ06cUJ8+fVRWVmbVDB48WFlZWUpLS1NaWpqysrKUlJR0lYYMAACqA4cxxlzJBgICAvTiiy/qscceU1hYmJKTkzVx4kRJ/zvrEhwcrJkzZ+rxxx+Xy+XSTTfdpOXLl2vgwIGSpB9//FHh4eF6//33lZCQoOzsbEVFRSkzM1MxMTGSpMzMTMXGxuo///mPIiMjL6tfRUVFcjqdcrlc8vf3v5IhAsANo8kf1ld1F3AdHZhxT1V34bqryN/vSt8TU1ZWplWrVunkyZOKjY3V/v37lZeXp169elk1Pj4+6tatm7Zs2SJJ2rlzp0pLS91qwsLCFB0dbdVs3bpVTqfTCjCS1LlzZzmdTqsGAADAs6Ir7Nq1S7Gxsfr5559Vr149paamKioqygoYwcHBbvXBwcH6/vvvJUl5eXny9vZWgwYNytXk5eVZNUFBQeX2GxQUZNWcT0lJiUpKSqz5oqKiig4NAADYSIXPxERGRiorK0uZmZl64okn9Mgjj+irr76yljscDrd6Y0y5tnOdW3O++kttJyUlxboR2Ol0Kjw8/HKHBAAAbKjCIcbb21u33nqrOnbsqJSUFLVt21YvvfSSQkJCJKnc2ZL8/Hzr7ExISIhOnTqlgoKCi9YcPny43H6PHDlS7izPL02aNEkul8uacnJyKjo0AABgI1f8OTHGGJWUlKhp06YKCQlRenq6tezUqVPKyMhQly5dJEkdOnSQl5eXW01ubq52795t1cTGxsrlcmn79u1WzbZt2+Ryuaya8/Hx8bEe/T47AQCA6qtC98Q8/fTTSkxMVHh4uI4fP65Vq1bp448/VlpamhwOh5KTkzV9+nQ1b95czZs31/Tp01WnTh0NHjxYkuR0OjVs2DCNHz9egYGBCggI0IQJE9S6dWvFx8dLklq2bKnevXtr+PDhWrBggSRpxIgR6tOnz2U/mQQAAKq/CoWYw4cPKykpSbm5uXI6nWrTpo3S0tLUs2dPSdJTTz2l4uJijRw5UgUFBYqJidGGDRvk5+dnbWPOnDny9PTUgAEDVFxcrB49emjJkiXy8PCwalauXKmxY8daTzH17dtX8+bNuxrjBQAA1cQVf07MjYrPiQFQHfE5MTULnxNzjT4nBgAAoCoRYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC0RYgAAgC1V6AsgYQ98t0rNUhO/WwUAJM7EAAAAmyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAWyLEAAAAW6pQiElJSVGnTp3k5+enoKAg3Xfffdq7d69bzdChQ+VwONymzp07u9WUlJRozJgxatiwoerWrau+ffvq0KFDbjUFBQVKSkqS0+mU0+lUUlKSCgsLKzdKAABQ7VQoxGRkZGjUqFHKzMxUenq6Tp8+rV69eunkyZNudb1791Zubq41vf/++27Lk5OTlZqaqlWrVmnz5s06ceKE+vTpo7KyMqtm8ODBysrKUlpamtLS0pSVlaWkpKQrGCoAAKhOPCtSnJaW5ja/ePFiBQUFaefOneratavV7uPjo5CQkPNuw+VyadGiRVq+fLni4+MlSStWrFB4eLg+/PBDJSQkKDs7W2lpacrMzFRMTIwkaeHChYqNjdXevXsVGRlZoUECAIDq54ruiXG5XJKkgIAAt/aPP/5YQUFBatGihYYPH678/Hxr2c6dO1VaWqpevXpZbWFhYYqOjtaWLVskSVu3bpXT6bQCjCR17txZTqfTqjlXSUmJioqK3CYAAFB9VTrEGGM0btw4/epXv1J0dLTVnpiYqJUrV2rjxo36y1/+oh07dqh79+4qKSmRJOXl5cnb21sNGjRw215wcLDy8vKsmqCgoHL7DAoKsmrOlZKSYt0/43Q6FR4eXtmhAQAAG6jQ5aRfGj16tL788ktt3rzZrX3gwIHWz9HR0erYsaMiIiK0fv16PfDAAxfcnjFGDofDmv/lzxeq+aVJkyZp3Lhx1nxRURFBBgCAaqxSZ2LGjBmjtWvXatOmTWrUqNFFa0NDQxUREaF9+/ZJkkJCQnTq1CkVFBS41eXn5ys4ONiqOXz4cLltHTlyxKo5l4+Pj/z9/d0mAABQfVUoxBhjNHr0aL333nvauHGjmjZtesl1jh49qpycHIWGhkqSOnToIC8vL6Wnp1s1ubm52r17t7p06SJJio2Nlcvl0vbt262abdu2yeVyWTUAAKBmq9DlpFGjRunNN9/UP/7xD/n5+Vn3pzidTvn6+urEiROaOnWq+vfvr9DQUB04cEBPP/20GjZsqPvvv9+qHTZsmMaPH6/AwEAFBARowoQJat26tfW0UsuWLdW7d28NHz5cCxYskCSNGDFCffr04ckkAAAgqYIhZv78+ZKkuLg4t/bFixdr6NCh8vDw0K5du7Rs2TIVFhYqNDRUd911l1avXi0/Pz+rfs6cOfL09NSAAQNUXFysHj16aMmSJfLw8LBqVq5cqbFjx1pPMfXt21fz5s2r7DgBAEA1U6EQY4y56HJfX1998MEHl9xO7dq19fLLL+vll1++YE1AQIBWrFhRke4BAIAahO9OAgAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtkSIAQAAtlShEJOSkqJOnTrJz89PQUFBuu+++7R37163GmOMpk6dqrCwMPn6+iouLk579uxxqykpKdGYMWPUsGFD1a1bV3379tWhQ4fcagoKCpSUlCSn0ymn06mkpCQVFhZWbpQAAKDaqVCIycjI0KhRo5SZman09HSdPn1avXr10smTJ62aWbNmafbs2Zo3b5527NihkJAQ9ezZU8ePH7dqkpOTlZqaqlWrVmnz5s06ceKE+vTpo7KyMqtm8ODBysrKUlpamtLS0pSVlaWkpKSrMGQAAFAdOIwxprIrHzlyREFBQcrIyFDXrl1ljFFYWJiSk5M1ceJESf876xIcHKyZM2fq8ccfl8vl0k033aTly5dr4MCBkqQff/xR4eHhev/995WQkKDs7GxFRUUpMzNTMTExkqTMzEzFxsbqP//5jyIjIy/Zt6KiIjmdTrlcLvn7+1d2iLbU5A/rq7oLuI4OzLinqruA64j3d81SE9/fFfn7fUX3xLhcLklSQECAJGn//v3Ky8tTr169rBofHx9169ZNW7ZskSTt3LlTpaWlbjVhYWGKjo62arZu3Sqn02kFGEnq3LmznE6nVXOukpISFRUVuU0AAKD6qnSIMcZo3Lhx+tWvfqXo6GhJUl5eniQpODjYrTY4ONhalpeXJ29vbzVo0OCiNUFBQeX2GRQUZNWcKyUlxbp/xul0Kjw8vLJDAwAANlDpEDN69Gh9+eWXeuutt8otczgcbvPGmHJt5zq35nz1F9vOpEmT5HK5rCknJ+dyhgEAAGyqUiFmzJgxWrt2rTZt2qRGjRpZ7SEhIZJU7mxJfn6+dXYmJCREp06dUkFBwUVrDh8+XG6/R44cKXeW5ywfHx/5+/u7TQAAoPqqUIgxxmj06NF67733tHHjRjVt2tRtedOmTRUSEqL09HSr7dSpU8rIyFCXLl0kSR06dJCXl5dbTW5urnbv3m3VxMbGyuVyafv27VbNtm3b5HK5rBoAAFCzeVakeNSoUXrzzTf1j3/8Q35+ftYZF6fTKV9fXzkcDiUnJ2v69Olq3ry5mjdvrunTp6tOnToaPHiwVTts2DCNHz9egYGBCggI0IQJE9S6dWvFx8dLklq2bKnevXtr+PDhWrBggSRpxIgR6tOnz2U9mQQAAKq/CoWY+fPnS5Li4uLc2hcvXqyhQ4dKkp566ikVFxdr5MiRKigoUExMjDZs2CA/Pz+rfs6cOfL09NSAAQNUXFysHj16aMmSJfLw8LBqVq5cqbFjx1pPMfXt21fz5s2rzBgBAEA1dEWfE3Mj43NiUFPUxM+RqMl4f9csNfH9fd0+JwYAAKCqEGIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtEWIAAIAtVTjE/Otf/9K9996rsLAwORwOrVmzxm350KFD5XA43KbOnTu71ZSUlGjMmDFq2LCh6tatq759++rQoUNuNQUFBUpKSpLT6ZTT6VRSUpIKCwsrPEAAAFA9VTjEnDx5Um3bttW8efMuWNO7d2/l5uZa0/vvv++2PDk5WampqVq1apU2b96sEydOqE+fPiorK7NqBg8erKysLKWlpSktLU1ZWVlKSkqqaHcBAEA15VnRFRITE5WYmHjRGh8fH4WEhJx3mcvl0qJFi7R8+XLFx8dLklasWKHw8HB9+OGHSkhIUHZ2ttLS0pSZmamYmBhJ0sKFCxUbG6u9e/cqMjKyot0GAADVzDW5J+bjjz9WUFCQWrRooeHDhys/P99atnPnTpWWlqpXr15WW1hYmKKjo7VlyxZJ0tatW+V0Oq0AI0mdO3eW0+m0agAAQM1W4TMxl5KYmKiHHnpIERER2r9/v5599ll1795dO3fulI+Pj/Ly8uTt7a0GDRq4rRccHKy8vDxJUl5enoKCgsptOygoyKo5V0lJiUpKSqz5oqKiqzgqAABwo7nqIWbgwIHWz9HR0erYsaMiIiK0fv16PfDAAxdczxgjh8Nhzf/y5wvV/FJKSoqmTZt2BT0HAAB2cs0fsQ4NDVVERIT27dsnSQoJCdGpU6dUUFDgVpefn6/g4GCr5vDhw+W2deTIEavmXJMmTZLL5bKmnJycqzwSAABwI7nmIebo0aPKyclRaGioJKlDhw7y8vJSenq6VZObm6vdu3erS5cukqTY2Fi5XC5t377dqtm2bZtcLpdVcy4fHx/5+/u7TQAAoPqq8OWkEydO6JtvvrHm9+/fr6ysLAUEBCggIEBTp05V//79FRoaqgMHDujpp59Ww4YNdf/990uSnE6nhg0bpvHjxyswMFABAQGaMGGCWrdubT2t1LJlS/Xu3VvDhw/XggULJEkjRoxQnz59eDIJAABIqkSI+fTTT3XXXXdZ8+PGjZMkPfLII5o/f7527dqlZcuWqbCwUKGhobrrrru0evVq+fn5WevMmTNHnp6eGjBggIqLi9WjRw8tWbJEHh4eVs3KlSs1duxY6ymmvn37XvSzaQAAQM3iMMaYqu7EtVBUVCSn0ymXy1XjLi01+cP6qu4CrqMDM+6p6i7gOuL9XbPUxPd3Rf5+891JAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAlggxAADAliocYv71r3/p3nvvVVhYmBwOh9asWeO23BijqVOnKiwsTL6+voqLi9OePXvcakpKSjRmzBg1bNhQdevWVd++fXXo0CG3moKCAiUlJcnpdMrpdCopKUmFhYUVHiAAAKieKhxiTp48qbZt22revHnnXT5r1izNnj1b8+bN044dOxQSEqKePXvq+PHjVk1ycrJSU1O1atUqbd68WSdOnFCfPn1UVlZm1QwePFhZWVlKS0tTWlqasrKylJSUVIkhAgCA6sizoiskJiYqMTHxvMuMMZo7d64mT56sBx54QJK0dOlSBQcH680339Tjjz8ul8ulRYsWafny5YqPj5ckrVixQuHh4frwww+VkJCg7OxspaWlKTMzUzExMZKkhQsXKjY2Vnv37lVkZGRlxwsAAKqJq3pPzP79+5WXl6devXpZbT4+PurWrZu2bNkiSdq5c6dKS0vdasLCwhQdHW3VbN26VU6n0wowktS5c2c5nU6r5lwlJSUqKipymwAAQPV1VUNMXl6eJCk4ONitPTg42FqWl5cnb29vNWjQ4KI1QUFB5bYfFBRk1ZwrJSXFun/G6XQqPDz8iscDAABuXNfk6SSHw+E2b4wp13auc2vOV3+x7UyaNEkul8uacnJyKtFzAABgF1c1xISEhEhSubMl+fn51tmZkJAQnTp1SgUFBRetOXz4cLntHzlypNxZnrN8fHzk7+/vNgEAgOrrqoaYpk2bKiQkROnp6VbbqVOnlJGRoS5dukiSOnToIC8vL7ea3Nxc7d6926qJjY2Vy+XS9u3brZpt27bJ5XJZNQAAoGar8NNJJ06c0DfffGPN79+/X1lZWQoICFDjxo2VnJys6dOnq3nz5mrevLmmT5+uOnXqaPDgwZIkp9OpYcOGafz48QoMDFRAQIAmTJig1q1bW08rtWzZUr1799bw4cO1YMECSdKIESPUp08fnkwCAACSKhFiPv30U911113W/Lhx4yRJjzzyiJYsWaKnnnpKxcXFGjlypAoKChQTE6MNGzbIz8/PWmfOnDny9PTUgAEDVFxcrB49emjJkiXy8PCwalauXKmxY8daTzH17dv3gp9NAwAAah6HMcZUdSeuhaKiIjmdTrlcrhp3f0yTP6yv6i7gOjow456q7gKuI97fNUtNfH9X5O83350EAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRADAABsiRAD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NGiQjh8/Lul/Z3cyMjL00ksvyeFwyOFw6MCBA5Kkr776Snfffbfq1aun4OBgJSUl6aeffrK2HRcXp7Fjx+qpp55SQECAQkJCNHXqVLf+7Nu3T127dlXt2rUVFRWl9PT0cn3etWuXunfvLl9fXwUGBmrEiBE6ceLElR0ooIYoLCzU5s2bNXPmTN11112KiIjQHXfcoUmTJumee+6RJB08eFD9+vVTvXr15O/vrwEDBujw4cPWNi71e2LZsmUKDAxUSUmJ27779++vhx9++PoNFtcNIQbXhIeHh6ZPn66XX35Zhw4duqx1vv32W61Zs0br1q3TunXrlJGRYV2SeumllxQbG6vhw4crNzdXubm5Cg8PV25urrp166Z27drp008/VVpamg4fPqwBAwa4bXvp0qWqW7eutm3bplmzZun555+3gsqZM2f0wAMPyMPDQ5mZmXrttdc0ceJEt/X/+9//qnfv3mrQoIF27Niht99+Wx9++KFGjx59FY4WUP3Vq1dP9erV05o1a8qFDOl/X/p333336dixY8rIyFB6erq+/fZbDRw40K3uYr8nHnroIZWVlWnt2rVW/U8//aR169bp0UcfvbYDRNUwwFX2yCOPmH79+hljjOncubN57LHHjDHGpKammrMvucWLFxun02mtM2XKFFOnTh1TVFRktf3+9783MTEx1ny3bt3Mk08+6bavZ5991vTq1cutLScnx0gye/futdb71a9+5VbTqVMnM3HiRGOMMR988IHx8PAwOTk51vJ//vOfRpJJTU01xhjz+uuvmwYNGpgTJ05YNevXrze1atUyeXl5l3togBrtnXfeMQ0aNDC1a9c2Xbp0MZMmTTJffPGFMcaYDRs2GA8PD3Pw4EGrfs+ePUaS2b59uzHm8n5PPPHEEyYxMdGanzt3rmnWrJk5c+bMtR4eqgBnYnBNzZw5U0uXLtVXX311ydomTZrIz8/Pmg8NDVV+fv5F19m5c6c2bdpk/S+vXr16uu222yT9739sZ7Vp08ZtvV9uOzs7W40bN1ajRo2s5bGxsW712dnZatu2rerWrWu13XnnnTpz5oz27t17ybEB+N9lnR9//FFr165VQkKCPv74Y7Vv315LlixRdna2wsPDFR4ebtVHRUWpfv36ys7Ottou9Xti+PDh2rBhg3744QdJ0uLFi62HDVD9EGJwTXXt2lUJCQl6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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=51730a63-1182-4389-b0d4-df46ca5bc178">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [10]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">decade_company</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">([</span><span class="s1">'Decade'</span><span class="p">,</span><span class="s1">'Company'</span><span class="p">])[</span><span class="s1">'Global_Sales'</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">unstack</span><span class="p">()</span><span class="o">.</span><span class="n">fillna</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>

<span class="n">decade_company</span> <span class="o">=</span> <span class="n">decade_company</span><span class="o">.</span><span class="n">reindex</span><span class="p">([</span><span class="mi">1980</span><span class="p">,</span><span class="mi">1990</span><span class="p">,</span><span class="mi">2000</span><span class="p">,</span><span class="mi">2010</span><span class="p">,</span><span class="mi">2020</span><span class="p">],</span> <span class="n">fill_value</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">decade_company</span><span class="o">.</span><span class="n">index</span><span class="p">))</span>
<span class="n">width</span> <span class="o">=</span> <span class="mf">0.4</span>

<span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">x</span> <span class="o">-</span> <span class="n">width</span><span class="o">/</span><span class="mi">2</span><span class="p">,</span> <span class="n">decade_company</span><span class="p">[</span><span class="s1">'Nintendo'</span><span class="p">],</span> <span class="n">width</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">'Nintendo'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">x</span> <span class="o">+</span> <span class="n">width</span><span class="o">/</span><span class="mi">2</span><span class="p">,</span> <span class="n">decade_company</span><span class="p">[</span><span class="s1">'Sony'</span><span class="p">],</span> <span class="n">width</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">'Sony'</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="p">[</span><span class="sa">f</span><span class="s2">"</span><span class="si">{</span><span class="n">i</span><span class="si">}</span><span class="s2">'s"</span> <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">decade_company</span><span class="o">.</span><span class="n">index</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">"Nintendo vs Sony Sales by Decade"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=aecd9ec6-b14a-4f25-b8c2-03fc0614cf31">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">year_sales</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">'Year'</span><span class="p">)[</span><span class="s1">'Global_Sales'</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>

<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">year_sales</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">year_sales</span><span class="o">.</span><span class="n">values</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">"Global Video Game Sales Over Time"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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TzoAIDg4GD169LCf/1Ku+p5erj7fg/ro378/hg4dihUrViA3NxeRkZFYvHgx7rvvPsyaNcuhbX5+PoKDg2s9V0hICBQKBcaPH4/HH3+8xjbx8fEAqpKGadOmYdq0aTh//jzWr1+P5557DsOGDUN6erpDb9KlbrzxRqxduxY//fRTjWvwCCGwcuVKhIaGonv37vbjDzzwAN58800sXboUd955J1auXImpU6dCoVDY24SHh6NTp0547bXXanzvy4vaG7pukTvZ/mD69NNPa32evAcTFGq0GTNm4Ndff8Wjjz6K77//vkHdwDfccAMAYPHixejZs6f9eGpqKo4cOWL/C92muLgYK1eudBgusa0FYZuRIpPJoFQqHT6Uy8vLG72mh4+PD8aNG4cFCxbgjTfeQGVl5VWHdwBg0KBB+Pbbb2uM+1JJSUlITEzE/v37q/3SvNzgwYOxfPlyZGZmOvxC+eKLL+Dn54devXrV+toePXpg6NChWLhwIe68807069fvqtfgqu/p5erzPahJTk4OIiIiqq0NYrFYcPz4cfj5+dmTD5lMBo1G49Dul19+wblz59C6deta38PPzw+DBg3C3r170alTp1pnsF0uODgY//jHP3Du3DlMnToVp0+ftifzl3vooYfw5ptvYsaMGbjhhhsQGRnp8PycOXNw9OhRvP766w7/7tq1a4eUlBR89tlnsFgsMBqNeOCBBxxeO3LkSKxatQoJCQk1ruvjjUaOHIlZs2YhLCzMnhyS92KCQo12/fXX44MPPsCUKVPQrVs3PPzww+jQoQPkcjmysrLwww8/AKhanKk2SUlJePjhh/H+++9DLpdjxIgROH36NF588UXExcXhqaeecmgfFhaGxx57DGfPnkWbNm2watUqLFy4EI899ph96OLmm2/G22+/jXHjxuHhhx9GQUEB3nrrrWq/jBpi4sSJ+OCDD/D222+jbdu26NOnz1Vfc9999+Gdd97Bfffdh9deew2JiYlYtWoV1qxZU63tRx99hBEjRmDYsGGYMGECmjVrhsLCQhw5cgR//vknvvvuOwDASy+9ZK8l+Pe//43Q0FB89dVX+OWXXzBnzpxq9SOXW7x4MYYNG4YhQ4ZgwoQJGDZsGCIjI2EwGHDgwAGsX7/e4b658nva0O9BTb788kt89NFHGDduHHr27AmtVouMjAx8/PHHOHz4MP7973/bE4qRI0di0aJFaNu2LTp16oQ9e/bgzTffrNaTV5N3330Xffv2Rb9+/fDYY4+hZcuWKC4uxokTJ/DTTz9hw4YNAIBRo0YhOTkZPXr0QEREBM6cOYN58+ahRYsWSExMrPX8wcHBWLZsGUaOHInu3bvbF50zGAz45ptv8NVXX+HOO+/Es88+W+21Dz74IB555BFkZmaiT58+1Xqc/vOf/2DdunXo06cPnnjiCSQlJaGiogKnT5/GqlWrsGDBgjp9DzzJ1KlT8cMPP6B///546qmn0KlTJ1itVpw9exZr167F008/jZSUFKnDpLqSuEiXmpB9+/aJBx54QMTHxwuNRiN8fHxE69atxX333Sd+++03h7Y1TTO2WCzijTfeEG3atBEqlUqEh4eLe++9V6Snpzu0sy3U9scff4gePXoIjUYjoqOjxXPPPVdtxsenn34qkpKShEajEa1atRKzZ88Wn3zyiQDgME2yrrN4LtW1a1cBQMyZM6fG52s6Z0ZGhrj99ttFQECACAwMFLfffrvYtm1bjVNn9+/fL8aOHSsiIyOFSqUSOp1O3HDDDWLBggUO7Q4ePChGjRoltFqtUKvVonPnzvVaTKyiokK8//77om/fviI4OFgolUoRGhoq+vXrJ9544w1RUFDg0L6u39MWLVqIm2++udr7oYbp4LXN9qjr9+Byf/31l3j66adFjx49REREhFAqlSIkJEQMGDCg2sJzRUVFYuLEiSIyMlL4+fmJvn37is2bN1e7f7Ut1JaWliYefPBB0axZM6FSqURERITo06ePePXVV+1t5s6dK/r06SPCw8OFWq0WzZs3FxMnThSnT5++4nXYnD17Vjz++OOiVatWQq1WC61WK/r37y8WL15c69RZvV4vfH19BQCxcOHCGtvk5eWJJ554QsTHxwuVSiVCQ0NF9+7dxfPPP2+f2tyYxdYaOovn0mUFhBDi/vvvF/7+/tXOUdOijSUlJeKFF14QSUlJ9u9Vx44dxVNPPVXjYnfkuWRCeNBGDkRERETgLB4iIiLyQExQiIiIyOMwQSEiIiKPwwSFiIiIPA4TFCIiIvI4TFCIiIjI43jlQm1WqxWZmZkIDAz0iuWXiYiIqGp7huLiYsTExFRb6flyXpmgZGZmVtu9lYiIiLxDenr6VVcq9soEJTAwEEDVBV5p+XQiIiLyHAaDAXFxcfbf41filQmKbVgnKCiICQoREZGXqUt5BotkiYiIyOMwQSEiIiKPwwSFiIiIPA4TFCIiIvI4TFCIiIjI4zBBISIiIo/DBIWIiIg8DhMUIiIi8jhMUIiIiMjjMEEhIiIij8MEhYiIiDwOExQiIiLyOF65WSAREVVXUGLEp1vTIATgr1EiQKO88F8F/NTKS44pEKBRwk+thFrJv1PJMzFBISJqAswWKx776k/sSius1+s0SjmeGJyIxwe1dlFkRA3DBIWIqAl4a+3f2JVWiACNErd3a4YykwWlJjNKjBaUGs1VD5MZpUYLSoxmmMxWAIDRbMU3qelMUMjjMEEhIvJyvx3JwYKNJwEAc/7RCTd1jL7qayotVmQUlWPQW38gvagMFZUW+KgUrg6VqM44+EhE5MXSC8vw1Df7AAAPXN+yTskJAKgUcrQM80OgjxJCAKcLSl0YJVH9MUEhIvJSRrMFjy/5E4YKM7o2D8aMEe3q9XqZTIaEiAAAwKk8JijkWZigEBF5qVd/PoIDGXoE+6kwf1y3Bs3IaRXhDwA4mVvi7PCIGoUJChGRF/px3zl8ueMMZDJg3p1d0CzYt0Hnsfeg5LMHhTwLExQiIi9zIrcYM5YdBABMHtQaA5MiG3wuW4JyMo89KORZmKAQEXmRMpMZjy3+E2UmC/okhGHqkDaNOl/CJUM8QghnhEjkFExQiIi8hBACzy8/hOO5JYgM1ODdu7pCIZc16pzNw/ygkMtQarIgt9jopEiJGo8JChGRl/h6VzqW7z0HhVyG+eO6ISJQ0+hzapQKxIVU1a+wUJY8CRMUIiIvcOicHjN/OgwAeHZYEq6LD3Xaue11KCyUJQ/CBIWIyMPpyyvx2Fd7YDJbMaRdJB7u18qp50+IvJCgsAeFPAgTFCIiDyaEwDPf7Ud6YTliQ3wx944ukDey7uRyrcKrCmU51Zg8CRMUIiIPtnDzKaz7KwdqhRwf3tMdWj+V09+DPSjkiZigEBF5qN2nC/HG6mMAgBdHtUfHWK1L3sfWg3LufDnKTRaXvAdRfdUrQZk5cyZkMpnDQ6fT2Z8XQmDmzJmIiYmBr68vBg4ciMOHDzucw2g0YsqUKQgPD4e/vz9Gjx6NjIwM51wNEVET8s76v2GxCozuHIN7U5q77H1C/dUIvtAzk8ZhHvIQ9e5B6dChA7KysuyPgwcP2p+bM2cO3n77bcyfPx+pqanQ6XS48cYbUVxcbG8zdepULF++HEuXLsWWLVtQUlKCkSNHwmJh1k5EZFNUasKOU4UAgGeGJkEmc27dyaUu3TSQK8qSp6h3gqJUKqHT6eyPiIgIAFW9J/PmzcPzzz+PMWPGIDk5GZ9//jnKysqwZMkSAIBer8cnn3yCuXPnYsiQIejatSsWL16MgwcPYv369c69MiIiL7b+SA4sVoF20UFoHubn8vezF8pyV2PyEPVOUI4fP46YmBjEx8fjrrvuwqlTpwAAaWlpyM7OxtChQ+1tNRoNBgwYgG3btgEA9uzZg8rKSoc2MTExSE5OtrepidFohMFgcHgQETVlaw5nAwCGd9BdpaVz2Atl2YNCHqJeCUpKSgq++OILrFmzBgsXLkR2djb69OmDgoICZGdX/WOKiopyeE1UVJT9uezsbKjVaoSEhNTapiazZ8+GVqu1P+Li4uoTNhGRVyk1mrHpeD4AYFhy1FVaO4etB4UJCnmKeiUoI0aMwO23346OHTtiyJAh+OWXXwAAn3/+ub3N5eOkQoirjp1erc2MGTOg1+vtj/T09PqETUTkVf44lgeT2YqWYX5Iigp0y3vaelBO5ZXCauWmgSS9Rk0z9vf3R8eOHXH8+HH7bJ7Le0Jyc3PtvSo6nQ4mkwlFRUW1tqmJRqNBUFCQw4OIqKlafWF4Z1iyzqXFsZdqHuoHpVyG8koLsg0VbnlPoitpVIJiNBpx5MgRREdHIz4+HjqdDuvWrbM/bzKZsHHjRvTp0wcA0L17d6hUKoc2WVlZOHTokL0NEdG1zGi24PejuQCAYW6qPwEAlUJuL8ZloSx5AmV9Gj/zzDMYNWoUmjdvjtzcXLz66qswGAy4//77IZPJMHXqVMyaNQuJiYlITEzErFmz4Ofnh3HjxgEAtFotJk6ciKeffhphYWEIDQ3FM888Yx8yIiK61m07UYASoxlRQRp0iQ1263snRATgVF4pTuaVoG9iuFvfm+hy9UpQMjIycPfddyM/Px8RERHo1asXduzYgRYtWgAApk+fjvLyckyaNAlFRUVISUnB2rVrERh4cQz1nXfegVKpxNixY1FeXo7Bgwdj0aJFUCgUzr0yIiIvZJu9M6yDzul77lxNqwjbVGMWypL0ZEIIr6uGMhgM0Gq10Ov1rEchoibDYhXo+dp6FJaa8NVDKbi+tXt7Mb7dnY7p3x9A39bhWPxQilvfm64N9fn9zb14iIg8ROrpQhSWmhDsp8J18aFuf3+uJkuehAkKEZGHsA3vDGkXBZXC/R/PCReGeLL0FSg1mt3+/kSXYoJCROQBhBBYc+hi/YkUgv3UCPNXA+CmgSQ9JihERB7g4Dk9MvUV8FMr0E/CGTS2QlkO85DUmKAQEXkA2/DOwKQI+Kikm9V4sQ6FPSgkLSYoREQeYLXEwzs2LJQlT8EEhYhIYidyi3EyrxRqhRw3tI2UNJaLa6GwB4WkxQSFiEhiaw7nAAD6tA5DoI9K0lhsPShp+SXcNJAkxQSFiEhituGd4RIP7wBAbIgvVAoZKiqtyNSXSx0OXcOYoBARSSijqAwHz+khlwFD2te+q7u7KBVytAyzzeThMA9JhwkKEZGE1l4Y3unRMhThARqJo6liG+bhnjwkJSYoREQSWn3Yc4Z3bLgWCnkCJihERBLJLzEi9XQhAGBYsuckKPapxrkc4iHpMEEhIpLI+r9yIATQsZkWzYJ9pQ7Hzj7VOJ89KCQdJihERBKxD+94UO8JALS60IOSYzCiuKJS4mjoWsUEhYhIAoaKSmw7UQBA+tVjL6f1VSEisKpgl5sGklSYoBARSeD3o7kwWaxIiPBH68gAqcOpplU4C2VJWkxQiIgksMZDh3dsEiJZKEvSYoJCRORmFZUW/HEsDwAwvEO0xNHUzNaDwkJZkgoTFCIiN9t8PB9lJguaBfsiuVmQ1OHUiD0oJDUmKEREbmbbe2dohyjIZDKJo6lZa9umgQWlsHDTQJIAExQiIjeqtFjx29Gq5e09afXYy8UE+0KtlMNktuJcETcNJPdjgkJE5Ea70gpxvqwSYf5q9GgZKnU4tVLIZRdn8rAOhSTABIWIyI1swzs3to+CQu6Zwzs29j15cpmgkPsxQSEichOrVWDtX1UJiiftvVMb+548eSyUJfdjgkJE5Cb7Ms4jx2BEgEaJPglhUodzVbYE5RQXayMJMEEhInKTNReGd25oGwmNUiFxNFdnH+JhDwpJgAkKEZGbrDtSNXvH0/beqY1t08D8EiP05dw0kNyLCQoRkRtk6ctxKq8UchnQr0241OHUSYBGiaigqk0DOcxD7sYEhYjIDbafrNq5uGNsMIJ8VBJHU3cX61A4zEPuxQSFiMgNtl1IULyhOPZSF2fysAeF3IsJChGRiwkh7D0o3pagXCyUZYJC7sUEhYjIxc4WluHc+XKoFDL0aOG5q8fWhEM8JBUmKERELmYb3unaPAS+as+fXnwpWw/K6YJSmC1WiaOhawkTFCIiF/PW+hMAiNH6wkclR6VFIIObBpIbMUEhInKhqvqTfABAnwTvmF58KblchvhwFsqS+zFBISJyoeO5JcgvMcFHJUeXuGCpw2mQBBbKkgSYoBARudC2E1W9Jz1bhkKt9M6PXBbKkhS8818LEZGXuFh/4n3DOzacakxSYIJCROQiFqvAjlPeWyBrwx4UkgITFCIiF/kr0wBDhRmBPkp0iAmSOpwGs/WgFJSacL7MJHE0dK1ggkJE5CLbLszeSYkPg1LhvR+3fmolYrQ+AICT7EUhN/HefzFERB7Om9c/uVxCJKcak3sxQSEicgGT2YrU04UAgD6tvT9BaRXOQllyLyYoREQucCDjPMpMFoT5q9EmMlDqcBrN1oPCQllyFyYoREQuYBve6ZUQBrlcJnE0jdeKq8mSmzFBISJygW325e29f3gHABIiq4Z4zhaUoZKbBpIbMEEhInKyikoL/jxzHoB3L9B2KV2QD/zUCpitAmcLy6QOh64BTFCIiJxsz5kimCxWRGt90DLMT+pwnEImk11cUTaXwzzkekxQiIiczDa80zshDDKZ99ef2NhXlM1noSy5HhMUIiInawr779TEXijLHhRyAyYoREROVFxRiQMZegBVPShNia1Qlj0o5A6NSlBmz54NmUyGqVOn2o8JITBz5kzExMTA19cXAwcOxOHDhx1eZzQaMWXKFISHh8Pf3x+jR49GRkZGY0IhIvIIqacLYbEKtAzzQ7NgX6nDcSrbEM+J3BIIISSOhpq6Bicoqamp+N///odOnTo5HJ8zZw7efvttzJ8/H6mpqdDpdLjxxhtRXFxsbzN16lQsX74cS5cuxZYtW1BSUoKRI0fCYrE0/EqIiDzAthNVwzu9m9jwDlCVoPiqFNCXV+JIVvHVX0DUCA1KUEpKSnDPPfdg4cKFCAkJsR8XQmDevHl4/vnnMWbMGCQnJ+Pzzz9HWVkZlixZAgDQ6/X45JNPMHfuXAwZMgRdu3bF4sWLcfDgQaxfv945V0VEJJGmtP/O5dRKuX3YatPxPImjoaauQQnK448/jptvvhlDhgxxOJ6Wlobs7GwMHTrUfkyj0WDAgAHYtm0bAGDPnj2orKx0aBMTE4Pk5GR7m8sZjUYYDAaHBxGRpykqNeGvrKrPp16tml6CAgD9E6t6hjb9zQSFXEtZ3xcsXboUf/75J1JTU6s9l52dDQCIiopyOB4VFYUzZ87Y26jVaoeeF1sb2+svN3v2bLz88sv1DZWIyK12nKrqPUmKCkREoEbiaFyjf5sIAMDu00UoM5nhp673rxGiOqlXD0p6ejqefPJJLF68GD4+PrW2u3zevxDiqmsBXKnNjBkzoNfr7Y/09PT6hE1E5Ba24Z2mNnvnUvHh/ogN8YXJYrUnZESuUK8EZc+ePcjNzUX37t2hVCqhVCqxceNGvPfee1Aqlfaek8t7QnJzc+3P6XQ6mEwmFBUV1drmchqNBkFBQQ4PIiJPs7WJ7b9TE5lMZu9F2fR3vsTRUFNWrwRl8ODBOHjwIPbt22d/9OjRA/fccw/27duHVq1aQafTYd26dfbXmEwmbNy4EX369AEAdO/eHSqVyqFNVlYWDh06ZG9DRORtsvUVOJVXCrkMSGmi9Sc2/RNtCQrrUMh16jV4GBgYiOTkZIdj/v7+CAsLsx+fOnUqZs2ahcTERCQmJmLWrFnw8/PDuHHjAABarRYTJ07E008/jbCwMISGhuKZZ55Bx44dqxXdEhF5i+2nqnoTkptpofVVSRyNa/VpHQaFXIZT+aVILyxDXGjT2G+IPIvTq5umT5+O8vJyTJo0CUVFRUhJScHatWsRGBhob/POO+9AqVRi7NixKC8vx+DBg7Fo0SIoFApnh0NE5BYX1z9p2r0nABDko0K35sFIPV2ETcfzcE9KC6lDoiZIJrxwOUCDwQCtVgu9Xs96FCKSnBACfd/4HefOl+PzB6/DgAs1Gk3Z+78dx9x1f2NYhyh8NL6H1OGQl6jP72/uxUNE1EjpheU4d74cSrkMPVuGXP0FTYCtUHbbiQJUWqwSR0NNERMUIqJG2nZh9k7X5sHXzLogyc20CPFTodhoxr7081KHQ00QExQioka6uP5J09t/pzYKuQx9OZuHXIgJChFRIwghmvT+O1fCZe/JlZigEBE1woncEuSXGKFRytG1ebDU4biVrQ7lwDk9CktNEkdDTQ0TFCKiRrD1nvRsGQqN8tpaKiEqyAdtdYEQAthygqvKknMxQSEiagRbgey1sP5JTS4ue89hHnIuJihERA1ksQrsOFUI4NqrP7GxLXu/+XgevHBZLfJgTFCIiBroSJYB+vJKBGiU6NhMK3U4kujRMgQ+KjlyDEYcyymWOhxqQpigEBE1kG14JyU+FErFtflx6qNSoNeFzRE3HuMwDznPtfkviojICS6uf3JtDu/Y2Hc3Ps4EhZyHCQoRUQMYzRbsSrPVn1w7C7TVxFYom5pWhDKTWeJoqKlggkJE1ACb/s5HmcmCqCAN2uoCr/6CJiwhwh/Ngn1hslix80LRMFFjMUEhImqAn/ZnAgBGdoqBXC6TOBppyWQy9G9T1Yu0kdONyUmYoBAR1VOZyYx1f+UAAEZ1jpE4Gs/AOhRyNiYoRET19NuRXJRXWtA81A+dY6/N6cWX69M6HAq5DKfySpFRVCZ1ONQEMEEhIqon2/DOqM7RkMmu7eEdG62vCl3iggFU1ecQNRYTFCKietCXV+KPC+t9cHjHkX2Yh3Uo5ARMUIiI6mHt4WyYLFYkRgYgKeranr1zOVuh7NaT+TBbrBJHQ96OCQoRUT38dCALADC6cwyHdy7TKTYYwX4qFFeYsS/9vNThkJdjgkJEVEcFJUZsPVFVX8HhneoUchmub13Vi8JhHmosJihERHW06lA2LFaBTrFatAz3lzocjzTgQh3KxuMslKXGYYJCRFRH9tk7ndh7Upt+F+pQDmScR1GpSeJoyJsxQSEiqoMsfTlST1ct435zp2iJo/Fc0VpftIkKgBDAlhPsRaGGY4JCRFQHvxzIghDAdS1DERPsK3U4Ho3TjckZmKAQEdXByksWZ6Mrs+1uvOl4HoQQEkdD3ooJChHRVZzOL8WBDD0UchlGdGSCcjXXxYdCo5Qjx2DE3zklUodDXooJChHRVfx8oKr3pE9CGMIDNBJH4/l8VAqktAoDwGEeajgmKEREV3FxeIezd+qqf+KF9VC4uzE1EBMUIqIrOJZdjL9zSqBWyDGsg07qcLzGgAt1KDvTClFuskgcDXkjJihERFdgW/tkQFIEtL4qiaPxHq0jAxCt9YHJbMXOtAKpwyEvxASFiKgWQggO7zSQTCa7ZLox10Oh+mOCQkRUiwMZepwtLIOvSoEh7SKlDsfrXDrdmKi+mKAQEdXC1nsypH0U/NRKiaPxPn1bh0MuA07kliBLXy51OORlmKAQEdXAahX26cWjuLR9g2j9VEjSBQEA9qeflzYY8jpMUIiIapB6uhA5BiMCfZQYkBQhdTheq2OzqgTl4Dm9xJGQt2GCQkRUA9vwzvAOOmiUComj8V4dm2kBAAfPGSSOhLwNExQiostUWqz49VA2AM7eaazkCwnKoXN67stD9cIEhYjoMttOFqCw1IQwfzX6JIRJHY5XaxcdBIVchsJSEzL1FVKHQ16ECQoR0WVW7qsa3rmpYzSUCn5MNoaPSoHEyAAAwMEM1qFQ3fFfHhHRJSoqLVh7uGp4Z3QXDu84Q8dLhnmI6ooJChHRJf44lodioxnRWh90bx4idThNQsdYW6EsExSqOyYoRESX+OnC2icjO0VDLpdJHE3T0JGFstQATFCIiC4oNZrx25EcAMDozs0kjqbpsBXKFpSakMVCWaojJihERBesP5KDikorWob5IfnCAmPUeA6FshzmoTpigkJEdMFPl+xcLJNxeMeZWChL9cUEhYgIgL6sEhv/rtp1dzQXZ3M6FspSfTFBISICsPF4HiotAm2iApAYFSh1OE0OV5Sl+mKCQkQEYMvxqt6TAW24MaArtL9QKJtfYkK2gYWydHVMUIjomieEwJbj+QCAvolMUFyBK8pSfTFBIaJr3qn8UmTqK6BWyHFdy1Cpw2myklkoS/XABIWIrnm23pPuLULgq1ZIHE3TZZvJw0JZqgsmKER0zdtsH94JlziSpi3ZnqAYWChLV1WvBOXDDz9Ep06dEBQUhKCgIPTu3Ru//vqr/XkhBGbOnImYmBj4+vpi4MCBOHz4sMM5jEYjpkyZgvDwcPj7+2P06NHIyMhwztUQEdVTpcWKHacKAAD9mKC4VPvoIMhlQH6JETkGo9ThkIerV4ISGxuL119/Hbt378bu3btxww034JZbbrEnIXPmzMHbb7+N+fPnIzU1FTqdDjfeeCOKi4vt55g6dSqWL1+OpUuXYsuWLSgpKcHIkSNhsVice2VERHWwP/08SoxmBPup0CFGK3U4TZqvWoHEyKop3BzmoaupV4IyatQo3HTTTWjTpg3atGmD1157DQEBAdixYweEEJg3bx6ef/55jBkzBsnJyfj8889RVlaGJUuWAAD0ej0++eQTzJ07F0OGDEHXrl2xePFiHDx4EOvXr6/1fY1GIwwGg8ODiMgZtpyoGt65PiEcCm4O6HLJrEOhOmpwDYrFYsHSpUtRWlqK3r17Iy0tDdnZ2Rg6dKi9jUajwYABA7Bt2zYAwJ49e1BZWenQJiYmBsnJyfY2NZk9eza0Wq39ERcX19CwiYgcbGH9iVt1vLDHEWfy0NXUO0E5ePAgAgICoNFo8Oijj2L58uVo3749srOzAQBRUVEO7aOiouzPZWdnQ61WIyQkpNY2NZkxYwb0er39kZ6eXt+wiYiqKa6oxN708wCAvq2ZoLgDl7ynulLW9wVJSUnYt28fzp8/jx9++AH3338/Nm7caH/+8g22hBBX3XTram00Gg00Gk19QyUiuqIdpwphsQq0DPNDXKif1OFcE9pHayGXAXnFRuQYKhAV5CN1SOSh6t2Dolar0bp1a/To0QOzZ89G586d8e6770Kn0wFAtZ6Q3Nxce6+KTqeDyWRCUVFRrW2IiNzFtrw9h3fcx1etQGuuKEt10Oh1UIQQMBqNiI+Ph06nw7p16+zPmUwmbNy4EX369AEAdO/eHSqVyqFNVlYWDh06ZG9DROQumy8UyPZtzeXt3YmFslQX9Rriee655zBixAjExcWhuLgYS5cuxR9//IHVq1dDJpNh6tSpmDVrFhITE5GYmIhZs2bBz88P48aNAwBotVpMnDgRTz/9NMLCwhAaGopnnnkGHTt2xJAhQ1xygURENck8X45TeaWQy4DeCWFSh3NN6dhMi2V/nmOhLF1RvRKUnJwcjB8/HllZWdBqtejUqRNWr16NG2+8EQAwffp0lJeXY9KkSSgqKkJKSgrWrl2LwMCLW5e/8847UCqVGDt2LMrLyzF48GAsWrQICgWXlyYi97HN3ukcFwytr0riaK4tXPKe6kImvHC9YYPBAK1WC71ej6CgIKnDISI3MVusUCqcs0PHlK/34qf9mXjihtaYNjTJKeekuikzmZH80hpYBbDzucEslL2G1Of3N/fiISKv8M66v5H04mqsPVz7kgR1ZbUKbLXVnySy/sTd/NRKJESwUJaujAkKEXm873an493fjsNiFXh73d+N3mjurywDCktN8Fcr0LV5sHOCpHrhMA9dDRMUIvJou9IK8dzyg/avj2YXY9vJgkad07a8fa9WYVA5aciI6sc2k4eFslQb/sskIo91tqAMj3y5G5UWgZs66nBvr+YAgE+2pDXqvFzeXnpcUZauhgkKEXkkQ0UlHvw8FUVllegUq8XcO7pgYt9WkMmADUdzcSK3pEHnrai0YNfpQgBAPyYokmkfHQSZDMgtNiLXUCF1OOSBmKAQkccxW6yYvGQvTuSWQBfkg4X39YCvWoH4cH8Mblu16vRnWxvWi5J6uhAmsxVRQRp7oSa5n7/mkkJZ9qJQDZigEJHHefWXI9j0dx58VHJ8fH8Ph2moE/vGAwB++DMDRaWmep/bPrzTOuKq+4SRa7FQlq6ECQoReZQvd5zBom2nAQDz7uxiL6a06dUqFO2jg1BRacWSXWfrff7NFxIUDu9Ij4WydCVMUIjIY2w+noeZKw8DAJ4dloThydHV2shkMjzUr6oX5fNtp2EyW+t8/vwSI/7KMgAArm/NBEVq7EGhK2GCQkQe4URuCSZ99ScsVoExXZth0sCEWtuO7BSDyEANcouN+PlAZp3fw7Y4W1tdICICNY2OmRqnQ0xVoWyOwYjcYhbKkiMmKEQkuaJSEyZ+noriCjO6twjB7Ns7XrE+RK2U4/4+LQFUTTmu68JtWzi841H8NUq0CvcHwGEeqo4JChFJymS24tHFe3CmoAyxIb74aHx3aJRX3zx03HXN4aOS43CmATvTCq/aXghhX6CNy9t7DvswT4ZB4kjI0zBBISLJCCHw4opD2JlWiACNEp/c3xPhAXUbegnxV+P2brEAgI83X33K8cm8UmTpK6BWyHFdy9BGxU3Ok8w6FKoFExQikszHm9Pwze50yGXA+3d3RZIusF6vf/DClOPfjuYgLb/0im1t9Sc9WobAV331Hhpyj46cyUO1YIJCRJLYcDQHs349AgB4/ub2GNQ2st7nSIgIwA1tIyHE1Rdu28zl7T1Sh2ZayGRAtqECecVGqcMhD8IEhYgk8e764xACuPu6ODx4fcsGn8e2cNt3uzOgL6ussU2lxYodp6o2GOzXmvUnniRAo0Q8C2WpBkxQiMjthBA4fmEvnar9dRq+omufhDC01QWivNKCr1NrXrhtf/p5lBjNCPFToUNMUIPfi1yD66FQTZigEJHb5RiMKDNZoJDL0DzUr1Hnkslk9l6URVtPo9JSfeE22/BOn9bhkMu5vL2nYYJCNWGCQkRudyqvqvckLsQXamXjP4ZGd4lBeIAG2YYKrDqYVe152/Tiflw91iNxyXuqCRMUInK7Uxdm3LRy0m7CGqUC9/VuAaD6wm2GikrsSz8PgAWynso27Jalr0B+CQtlqQoTFCJyu1N5VQmKrTjSGe5JaQ61Uo4DGXrsPlNkP77jZAEsVoH4cH/EhjRuOIlcI9BHZV9RlsM8ZMMEhYjcLi2/aojHmQlKWIAGt3drBgD4ePMp+3H76rEc3vFoHWMvDPNkMEGhKkxQiMjt0uxDPM5LUADgweurimXX/pWDswVlAC7uv8PhHc/GQlm6HBMUInIrk9mK9KJyAECrcOfUoNgkRgViQJuIqoXbtqXh3PlynMovhUIuQ++EMKe+FzkXC2XpckxQiMitzhaWwWIV8FMrEBVUt3136sM25fjb1HT8emFGT+dYLYJ8VE5/L3IeW6Fspr4CBfUslC0xml0REkmMCQoRuZVtinF8uH+jFmirTb/EcLSJCkCpyYK5a/8GwPoTb1DfQtmKSgu+35OBWz7YiuSX1uDxJX8it7jC1WGSGzFBISK3SnPyFOPLXbpwW3mlBQDQN5HL23uDugzznM4vxWu//IVes3/DM9/tx/4LU8h/OZCFIXM34tvUdIdp5uS9mKAQkVu5Yorx5W7p0gxh/moAgL9aga7Ng132XuQ8tRXKmi1WrD2cjfs+3YWBb/2BhZvTcL6sEs2CffHssCQseSgFyc2CYKgwY/oPBzBu4c6r7m5Nnk8pdQBEdG2x/eJIcPIMnkv5qBQY37sF5q0/jutbh0Ol4N9i3uBiD4oBAJBbXIFvU9OxZOdZZOqrhm9kMmBAmwiM79UCA5MiobiwdcGKSdfjs62nMXfdMWw/VYBh8zbhycGJeLh/K95/L8UEhYjcyraKrCt7UADg8UGtERnog0FtObzjLTo0qyqUPXe+HI9+uQfrj+TAbK0argnxU2Fszzjcc10LNA+rvuCeUiHHP/u3wrAOOjy/4iA2H8/Hm2uO4af9mXj99k7oEhfszkshJ2CCQkRuY6iotC9l7uoERaWQY1xKc5e+BzlXkI8K8eH+SMsvxerD2QCAbs2DcW+vFripYzR8VIqrnqN5mB++ePA6LN97Dq/8/BeOZhdjzH+3YkKfeDw9tA38Nfy15y14p4jIbdIu1J9EBGoQyGm/VINx1zXH/zafwpB2kbgnpYV92Kc+ZDIZxnSLxYA2EXjl57+wYl8mPt2ahjWHs/HqbckYlBTpgsjJ2ZigEJHbnHLBEvfUtPyzfyv8s38rp5wrLECDeXd1xW3dYvHcsoM4d74cD3yWitGdY/Dy6A4IuVBITZ6JlUNE5Da2HhRXFsgSXW5Amwism9YfD/WNh1wGrNyfiWe+2y91WHQVTFCIyG1OuqlAluhyfmolXhjZHt8+0hsAsOFYLjKKyiSOiq6ECQoRuY2tB8XZe/AQ1VWPlqHokxAGIYBvd2dIHQ5dARMUInILIYR9DZR4DvGQhO66rmp213e702GxctVZT8UEhYjcIttQgfJKCxRyGeJCqq9jQeQuQ9tHIdhPhSx9BTYdz5M6HKoFExQicgvb8E7zUD+olfzoIen4qBS4rWszAMA3u9IljoZqw08JInILFsiSJ7mzZxwAYP2RHOQVGyWOhmrCBIWI3OJigSwTFJJeW10QusQFw2wVWPYni2U9ERMUInIL+yJtLJAlD3HXhV6Ub1LTIQSLZT0NExQicgvbDB5OMSZPMapzDPzVCpzKL8WutEKpw6HLMEEhIpczma1IL6xaFKsVe1DIQ/hrlBjVOQZAVS8KeRYmKETkcmcLS2EVgL9agchAjdThENnZimV/OZgFfXmlxNHQpZigEJHLncq7uECbTCaTOBqii7rEBSMpKhBGsxUr952TOhy6BBMUInK5U/Ypxqw/Ic8ik8nsvShLOczjUZigEJHLcYoxebLbujaDWiHH4UwDDmbopQ6HLmCCQkQuZ5tizAJZ8kQh/moMT9YBAJamnpU4GrJhgkJELscpxuTpbGuirNyXiTKTWeJoCGCCQkQupi+vRH6JCQDQMpybBJJn6tUqDM1D/VBsNGPVwWypwyEwQSEiF7P1nkQEahDoo5I4GqKayeUXi2W/4TCPR6hXgjJ79mz07NkTgYGBiIyMxK233opjx445tBFCYObMmYiJiYGvry8GDhyIw4cPO7QxGo2YMmUKwsPD4e/vj9GjRyMjg3shEDVFabb6ExbIkof7R/dYyGVA6ukinMgtkTqca169EpSNGzfi8ccfx44dO7Bu3TqYzWYMHToUpaWl9jZz5szB22+/jfnz5yM1NRU6nQ433ngjiouL7W2mTp2K5cuXY+nSpdiyZQtKSkowcuRIWCwW510ZEXkE2xooLJAlTxcV5IMb2kYCYC+KJ6hXgrJ69WpMmDABHTp0QOfOnfHZZ5/h7Nmz2LNnD4Cq3pN58+bh+eefx5gxY5CcnIzPP/8cZWVlWLJkCQBAr9fjk08+wdy5czFkyBB07doVixcvxsGDB7F+/XrnXyERSeoUC2TJi9zVszkA4Ic/z8FktkoczbWtUTUoen3VfPHQ0FAAQFpaGrKzszF06FB7G41GgwEDBmDbtm0AgD179qCystKhTUxMDJKTk+1tLmc0GmEwGBweROQd7KvIcoiHvMDApAhEBmpQWGrC+iM5UodzTWtwgiKEwLRp09C3b18kJycDALKzqyqfo6KiHNpGRUXZn8vOzoZarUZISEitbS43e/ZsaLVa+yMuLq6hYRORG1mtAqfzOcRD3kOpkOOOHrEAuLKs1BqcoEyePBkHDhzA119/Xe25y/faEEJcdf+NK7WZMWMG9Hq9/ZGezh8aIm+QU1yB8koLFHIZ4kI5xZi8w9geVX8Ebz6eh4yiMomjuXY1KEGZMmUKVq5cid9//x2xsbH24zpd1Up8l/eE5Obm2ntVdDodTCYTioqKam1zOY1Gg6CgIIcHEXk+2/BO81A/qBRc1YC8Q4swf/RJCIMQwHe7OcNUKvX6xBBCYPLkyVi2bBk2bNiA+Ph4h+fj4+Oh0+mwbt06+zGTyYSNGzeiT58+AIDu3btDpVI5tMnKysKhQ4fsbYioabhYIMvhHfIutjVRvtudDotVSBzNtUlZn8aPP/44lixZgh9//BGBgYH2nhKtVgtfX1/IZDJMnToVs2bNQmJiIhITEzFr1iz4+flh3Lhx9rYTJ07E008/jbCwMISGhuKZZ55Bx44dMWTIEOdfIRFJ5lRe1VoSLJAlbzOsgw7Bfipk6iuw6XgeBiVFSh3SNadeCcqHH34IABg4cKDD8c8++wwTJkwAAEyfPh3l5eWYNGkSioqKkJKSgrVr1yIwMNDe/p133oFSqcTYsWNRXl6OwYMHY9GiRVAoFI27GiLyKPY9eCI4xZi8i49Kgdu6NsNnW0/jm13pTFAkIBNCeF3flcFggFarhV6vZz0KkQfrP+d3nC0sw9f/7IXeCWFSh0NUL0ezDRg+bzOUchm2zxiMiECN1CF5vfr8/mbVGhG5hNFssc+ASOAUY/JCbXVB6BIXDLNVYNmfLJZ1NyYoROQS6YVlsArAX63gX57kte66UCz7AxMUt2OCQkQucdK2gmyE/1XXQSLyVDe0q6o9OZ5bAqOZ+8W5ExMUInKJNO7BQ01ARIAGARolhADOFnDRNndigkJELsEpxtQUyGQy+8+wLekm92CCQkQukcY9eKiJYIIiDSYoROQSHOKhpqIlExRJMEEhIqfTl1civ8QEoKpIlsibtWKCIgkmKETkdLYP8sjAqgJDIm/GIR5pMEEhIqdjgSw1JbYhntxiI0qMZomjuXYwQSG6RujLK2F1066s3IOHmhKtrwph/moAwGn2orgNExSia8DWE/no/so6TP76T7ckKafybAWy7EGhpoHDPO7HBIWoiTOZrXhxxSGYrQKrDmZjwaaTLn/PU5xiTE0MExT3Y4JC1MQt2paGU/ml0Cir/rm/teYYtp3Md9n7Wa3C3g3OGhRqKjjV2P2YoBA1YbmGCry7/jgA4NVbk3F7t1hYBfDE13uRY6hwyXtmGypQXmmBUi5DXKifS96DyN041dj9mKAQNWGvrz6KUpMFXeKCcXu3WLx6azLa6gKRX2LC5CV/otJidfp72j7Am4f6QaXgRww1Dbb1fE7llUAI9xSbX+v46UHURO05U4hlf54DALw8ugPkchl81Qp8eG93BGqUSD1dhDmrjzr9fTnFmJqilmFVP8+GCjOKyioljubawASFqAmyWAVmrvwLADC2Ryw6xwXbn4sP98ebd3QCACzcnIbVh7Kc+t4skKWmyEelQIzWBwCQll8icTTXBiYoRE3Qt7vTcfCcHoEaJaYPb1vt+eHJ0fhnv3gAwLPfHXDquLptinE89+ChJsY2zJOWXyZxJNcGJihETYy+rBJvrjkGAJh6YxuEB2hqbDd9eFtc1zIUxUYzHlu8B+Umi1Pen7sYU1N1caoxe1DcgQkKURPzzvq/UVhqQmJkAO7r3aLWdiqFHPPHdUV4gAZHs4vx/IqDjS7+M5otyCiq+uuSi7RRU2OrQ+FMHvdggkLUhBzLLsaXO84AAF4a1eGqs2gig3zw/t1dIZcBy/48h693pTfq/c8WlMEqgACNEhGBNffcEHmrVhzicSsmKERNhBACM1cehsUqMLyDDn0Tw+v0ut4JYXh2WFWdysyVh3EwQ9/gGE5dskCbTCZr8HmIPJGtrup0fqnb9rW6ljFBIWoiVh3MxvZTBdAo5Xj+5nb1eu2jA1phSLsomCxWPPbVHpwvMzUohosFshzeoaYnNsQXSrkM5ZUW5BS7ZqFDuogJClETUG6y4LVfqqYVPzogod4ruMpkMswd2xnNQ/2QUVSOad/ub9BfiLbiQRbIUlOkUsjt/7bS8liH4mpMUIiagA//OIFMfQWaBfvisYEJDTqH1leFD+/tBo1Sjg1Hc/HhxvpvKsgeFGrq7DN5CpiguBoTFCIvl15YhgWbTgEAXri5HXxUigafq0OMFq/ckgwAmLv2GDYfz6vX622zGxIiuAYKNU32BIU9KC7HBIXIy73y818wma3okxCG4cm6Rp9vbM84jO1Rtang/Z/uwpNL9+J4TvFVX6cvq0RBaVXtSkv2oFATxV2N3YcJCpEX2/R3Htb+lQOFXIaZozs4bebMf25JxohkHawC+HFfJobO24RJX+3BX5mGWl9z6kL9SVSQBgEapVPiIPI0rTjE4zZMUIi8VKXFipd/OgwAuK93C7SJCnTauX1UVZsK/jylL4Z1iIIQVbOEbnpvMx76fDcOZJyv9pq0fNafUNNn+/k+W1AGswt2A6eLmKAQeanPt53GybxShPmrMXVIG5e8R3IzLT4a3wOrp/bDyE7RkMmA9UdyMHr+Vtz/6S7sOVNob8s9eOhaoAvygY9KDrNVIKOoXOpwmjQmKEReKLe4AvPWHwcATB+eBK2vyqXv11YXhPnjumH9tAEY060ZFHIZNv6dh9s/3I67/7cD207m24d4EjjFmJowuVzGJe/dhAkKkZcRQuDFFYdQYjSjU6wWd3SPc9t7J0QE4O2xXbDh6QG4q2ccVAoZtp8qwLiFO7H6UDYADvFQ0xfPQlm3YIJC5GW+2nkWaw7nQKWQYdZtHSGXu39J+RZh/nj99k7449lBGN+rBdRKOWzrunGKMTV1TFDcg6X2RF7kWHYxXvm5asXYfw1vi+RmWknjaRbsi1duTcbkG1rjs62noZADLcLqt4otkbfhVGP3YIJC5CUqKi2Y8vWfMJqtGJgUgQevj5c6JLuoIB/834i2UodB5BatmKC4BYd4iLzEq7/8hb9zShAeoMFbd3SWZGiHiC4O8WTqy1FRaZE4mqaLCQqRF1h9KBuLd5wFALxzZ2eEB2gkjojo2hXqr0aQjxJCAGcKyqQOp8ligkLk4TLPl+NfPxwAADzSvxX6JUZIHBHRtU0mk7FQ1g2YoBB5MItVYOrSfdCXV6JTrBZPD02SOiQiAmfyuAMTFCIPNn/DCew6XQh/tQLv3dUVaiX/yRJ5AtuKyWkXFigk5+OnHZGHSj1diHd/+xsA8OptydwhmMiDtAyvmk7PHhTXYYJC5IH0ZZV48uu9sApgTNdmuK1rrNQhEdElWtl7UFgk6ypMUIg8jBAC/7fsADL1FWgZ5of/3JosdUhEdBlbD0p+iRGGikqJo2mamKAQeZivd6Xj10PZUMpleO/urgjQcD1FIk8T6KNCRGDVdP/THOZxCSYoRB7k75xivPzTYQBVuxR3ig2WNiAiqlU8dzV2KSYoRB6iotKCJ77eC6PZin6J4XiobyupQyKiK+BUY9digkLkIV775QiOZhcjPECNuWO5lD2Rp4uPYILiSkxQiDzA2sPZ+HLHGQDAW3d0RmSgj8QREdHVtOQQj0sxQSGSmMUqMGvVEQDAQ33jMTApUuKIiKguWl3SgyKEkDiapocJCpHE1v2Vg9MFZdD6qvDUjW2kDoeI6qh5qB9kMqC4woyCUpPU4TQ5TFCIJLZw8ykAwL29msOfU4qJvIaPSoEYrS8ADvO4Qr0TlE2bNmHUqFGIiYmBTCbDihUrHJ4XQmDmzJmIiYmBr68vBg4ciMOHDzu0MRqNmDJlCsLDw+Hv74/Ro0cjIyOjURdC5I32nCnEnjNFUCvkuL93S6nDIaJ6asVCWZepd4JSWlqKzp07Y/78+TU+P2fOHLz99tuYP38+UlNTodPpcOONN6K4uNjeZurUqVi+fDmWLl2KLVu2oKSkBCNHjoTFYmn4lRB5oYWb0gAAt3aNQWQQC2OJvA2nGrtOvfuTR4wYgREjRtT4nBAC8+bNw/PPP48xY8YAAD7//HNERUVhyZIleOSRR6DX6/HJJ5/gyy+/xJAhQwAAixcvRlxcHNavX49hw4Y14nKIvMfp/FKs+SsbAPBQP655QuSN7AlKHhMUZ3NqDUpaWhqys7MxdOhQ+zGNRoMBAwZg27ZtAIA9e/agsrLSoU1MTAySk5PtbS5nNBphMBgcHkTe7pMtaRACGJQUgTZRgVKHQ0QN0JI9KC7j1AQlO7vqr8GoqCiH41FRUfbnsrOzoVarERISUmuby82ePRtardb+iIuLc2bYRG5XVGrCd3vSAQD/7M/eEyJv1epCgnK6oBRWK6caO5NLZvHIZI4rYAohqh273JXazJgxA3q93v5IT093WqxEUli84wwqKq1IbhaE3q3CpA6HiBqoWbAvVAoZjGYrsgwVUofTpDg1QdHpdABQrSckNzfX3qui0+lgMplQVFRUa5vLaTQaBAUFOTyIvFVFpQWfbz8NAPhnv1ZXTd6JyHMpFXLEhfoBYB2Kszk1QYmPj4dOp8O6devsx0wmEzZu3Ig+ffoAALp37w6VSuXQJisrC4cOHbK3IWrKVuw9h/wSE2K0PripY7TU4RBRI9mGedIKmKA4U71n8ZSUlODEiRP2r9PS0rBv3z6EhoaiefPmmDp1KmbNmoXExEQkJiZi1qxZ8PPzw7hx4wAAWq0WEydOxNNPP42wsDCEhobimWeeQceOHe2zeoiaKqtV2Bdme7BvPFQKrpVI5O04k8c16p2g7N69G4MGDbJ/PW3aNADA/fffj0WLFmH69OkoLy/HpEmTUFRUhJSUFKxduxaBgRdnKbzzzjtQKpUYO3YsysvLMXjwYCxatAgKhcIJl0TkuX4/louTeaUI1ChxZ08WexM1BfHhAQCAtPwSiSNpWmTCC3c4MhgM0Gq10Ov1rEchr3LnR9uxM60Qj/RvhRk3tZM6HCJygm0n8zFu4U60DPPDH88OuvoLrmH1+f3N/mUiN9mffh470wqhlMsw4fqWUodDRE7S6kIPSnpROSotVomjaTqYoBC5ia32ZHTnGERf2GCMiLxfVJAGvioFLFaB9MIyqcNpMpigELlBemEZfj3EZe2JmiKZTMYVZV2ACQqRG3y29TQsVoF+ieFoH8O6KaKmphUTFKdjgkLkYvqySixNPQugamE2Imp6uKux8zFBIXKxJbvOosxkQVtdIPolhksdDhG5ABMU52OCQuRCJrMVn21NA8Bl7YmaMtagOB8TFCIXWrk/E7nFRkQFaTCqc4zU4RCRi9hqULL0FSg3WSSOpmlggkLkIkIILNxUNbX4gevjoVbynxtRUxXir0awnwoAcJp78jgFPzGJXGTT8XwcyymGv1qBu69rLnU4RORiLcM4zONMTFCIXMTWe3Jnz+bQ+qokjoaIXI1TjZ2LCQqRC/yVacCWE/lQyGV4gMvaE10TOJPHuZigELnA/zadBADc1DEacaF+EkdDRO4QH8EExZmYoBA52aa/87BiXyYA4GEuzEZ0zWANinMxQSFyooISI57+bj8A4L7eLdAxVitxRETkLrYhnsJSE/RllRJH4/2YoBA5iRAC//rhAPKKjWgTFYDnbmondUhE5Eb+GiWigjQAgDRONW40JihETrJ451msP5ILtUKOd+/qCh+VQuqQiMjNLg7zlEgcifdjgkLkBMdzivHqz38BAP41oi3aRXPHYqJrUSt7oWyZxJF4PyYoRI1kNFvwxNJ9MJqt6N8mAg/0aSl1SEQkEU41dh4mKESNNGf1MRzJMiDMX4237ugEuZwbAhJdq+LDAwBwiMcZmKAQNcKmv/PwyZaq3Yrn/KMTIgN9JI6IiKQUH1617lFaXimEEBJH492YoLiJEAIZRWX47UgONv6dB6uVP7je7vIpxYPbRUkcERFJLS7UDwq5DKUmC04XsA6lMZRSB9AUnS8z4Vh2MY7lFONodjGOZRfj7+xiFBvN9jY3d4rG3Ds6c6aHlxJCYPr3nFJMRI40SgX6JIRh8/F8/HIgE5NvSJQ6JK/FBKWRcgwV2HJh19qqZMSAHIOxxrYqhQytwgNwKr8EvxzIQl6xEQvH94DWjxvJeZvFO87gt6OcUkxE1Y3qHIPNx/Px475MPD6oNWQy1qU1BBOURig3WTDq/S3ILa6ekMSG+KKtLhBJukC0iQpEW10Q4sP9oVbKse1EPh75cg92pRXiHwu2YdGD16FZsK8EV0ANcTynGK/+cgQApxQTUXXDOujwwvJDOJ5bgqPZxfyMaCAmKI3w1c4zyC02IjxAjZs7RiNJF3QhIQlAoE/tvSJ9Wofj20d7Y8Jnu3A8twRj/rsVix64jj/EXoBTionoarS+KgxqG4E1h3Owcn8mP9sbiEWyDVRRacFHm04BAJ4dloSXb0nGuJTm6N4i5IrJiU276CAsm3Q9EiMDkGMwYuyC7dh2It/VYdeIleZ1xynFRFQXozs3AwCs3JfJz9gGYoLSQEt3nUVesRHNgn1xW9fYBp2jWbAvvn+0D1LiQ1FsNOP+z3bhx33nnBzplR3PKUbP137DY4v3XFP/iHINFcgtrqjXNXNKMRHV1eB2kfBXK3DufDn+PFskdTheiUM8DVBRacGHG08CACYNSoBa2fA8T+unwhcTr8O0b/fjlwNZeHLpPmSer8CjA1q5vLCq1GjGY1/9ifwSI349lI1tJwtwfetwp7+PEAIWq4BSIW0+LITAtpMFWLj5FP44lgcA0CjlaBbii9gQP8SG+F54VP1/XIgfwgPUkMlknFJMRPXio1JgWAcdlu09h5X7MtG9RajUIXkdJigN8N2eDOQYjIjW+uAf3RvWe3IpjVKB9+/qiuggH3y8JQ1vrD6KLH05XhrVAQoXDSEIIfD88oM4kXtxtcM31xxDn4QwpyZGQgg8sXQftp3Ix/xx3dA7Icxp566rSosVPx/IxMJNafgrywAAsF2i0WzFqbxSnMqreVlqjVKO2BBfmK2CU4qJqF5GdYnBsr3n8MvBLLw4sr3kf6R5GyYo9WQyW/Hh7ycAAI8OSIBG6ZzppXK5DC+MbA+d1gevrTqCL7afQY6hwmVTWJfsOosV+zKhkMvw/t1dMe3bfdiXfh4bjuY6tXdg/ZFc/LQ/EwDw4KJUfP7gdbgu3j1/SejLK/H1rrNYtPU0sg0VAABflQJje8Tiwb7xiNb6IltfgYyiMmQUlV/y36r/zzJUwGi24uSF5IVTiomoPvq2Dkeovxr5JSZsO1mA/m0ipA7JqzBBqadlf2YgU1+ByEAN7uwZ5/TzP9SvFaK1vnjqm31YczgH93y8Ex/f1wMh/mqnvcehc3q8vLJq593pw5JwU8doHMjQY8HGk3hr7d8YlBTplOJPk9mKWauqpuOG+qtRWGrChM924cuJ17m0uzO9sAyfbT2Nb1LPotRkAQBEBGowoU9L3JPSHMF+F7+XzcP80DzMr9b4L01g2ugCWY1PRHWmUshxU0cdFu84i5X7M5mg1BP7m+qh0mLFB39U9Z48MiDBZX9J39wpGl9OvA5BPkrsOVOE2xdsQ3qhc5ZM1pdX4rGv9sBksWJIuyg83L8VAOCR/q0QqFHiSJYBvx7Kdsp7Ld5xBmn5pQgPUGPtU/3Rt3U4ykwW3P9pKva6oGhsX/p5PL7kTwx483d8ujUNpSYLkqICMecfnbDlX4Pw+KDWDsnJ1aiVcjQP80Of1uEY2zMOXeKCnR4zETVtttk8aw5lo6LSInE03oUJSj2s2HsO6YXlCA9QY9x1zV36XimtwvD9Y30Qo/XBqbxS3PbfrdiXfr5R5xRC4Nnv9iO9sByxIb6Ye0dne71JiL8aE/vFAwDeXncMlkbuFXS+zIR3fzsOAHh6aBLCAzRYeF8P9GoVihKjGfd9sgsHMhp3PTYHMs5j7ILtuPWDrfjlQBasAuiXGI7PH7wOq6f2w9gecU4biiMiqo8eLUIQo/VBsdGMP47lSh2OV2GCUkdmixUfXKg9ebh/K/iqXf8Lr01UIJZNuh7to4OQX2LCXf/bjtWN6N34eHMa1v6VA7VCjg/v6V5tif2JfeMR7KfCybxSrNjbuOnO89Yfh768Em11gRjbo2oozFetwKcTeuK6llXTqu/9eCcOndM3+D0qKi14/dejuPWDrdh1uhAqhQxjujXDqif64cuJKRjQJoJLTBORpORyGUZ1jgEA/LgvU+JovAsTlDr66UAmTheUIdRfjXtSWrjtfXVaH3z7aG8MSopARaUVj321Bx9vPlXvNUt2ny7E66uPAgBeHNUeHWO11doE+qjw6IAEAMC83/6GyWxtUMwn80qweMcZAMALN7d3mInkp1bi0wd6onuLEBgqzLj3k534K9NQ7/fYc6YQN723GQs2noRVAKM7x2Dz9Bvw9tguaB/DOhEi8hyju1QlKL8dzUVxRaXE0XgPJih1YLEKzN9Q1XsysW88/DXurS0O0Cix8L4euCelOYQAXv3lCGauPFznYZiCEiMmL9kLi1VgdOcY3JtS+/DU/b1bIjxAg/TCcny7O71B8c5edQRmq8DgtpHom1h9XZUAjRKLHuiJLnHBOF9WiXs/2Ylj2cV1OneZyYyXfzqMfyzYjlN5pYgM1OB/47vjvbu7QqflwmlE5HnaRwchIcIfJrMVaw/nSB2O12CCUgerDmbhZF4ptL4q3Nfbfb0nl1Iq5Hj11mQ8d1NbAMDn28/g4S92o9RovuLrLFaBqd/sQ7ahAgkR/pg9puMVhz181QpMHlTVi/L+huP1LuraeiIf64/kQimX4bmba18vJNBHhc8fvA6dYrUoLDXhno934ETulZOUbSfzMXzeZny29TSEAO7oHot1Tw3A0A66esVIROROMpnMXiz7434O89QVE5SrsFoF3t9QVew5sW98nfbZcRWZTIaH+yfgv/d0g0Ypx29Hc3Hn/7Yj98IaHzV5f8NxbD6eDx+VHB/e271OvT93pzRHjNYHOQajfaimLixWgVd+rpq+fG+vFkiICLhie62vCl8+mIIOMVU1Nncv3ImTeSXV2pUYzXh++UGMW7gTZwvLEKP1wecPXoc37+hcrY6GiMgT2YZ5tp7IR36JUeJovAMTlKtYczgbf+eUINBHifs9ZOfamzpGY8k/eyHUX41D5wy49YOtNQ6RbDmeb59J89qtHdEmKrBO59coFXhicCIA4MM/Tl61l8bmu93pOJpdjCAfJZ688Pqr0fqpsHhiCtrqApFXbMS4hTtwOv/iqq4b/87DsHc24audZwEA96Q0x5qn+mMA1xMgIi8SH+6PTrFaWKwCqw5mSR2OV2CCcgVCCLx3ofbkgevjofX1nL/Wu7cIwfJJfdAq3B+Z+gr848Nt2HL84m7I2foKPLl0L4QA7uoZh9vruST/7d1j0TLMDwWlJizadvqq7UuMZry19m8AwBODE+u1sFyIvxpfPZSCNlFVOzvfvXAHDp3T49nv9uP+T3fh3PlyNA/1w5J/puC12zpK2otFRNRQoy/M5lnJ2Tx1wgTlCtYfycWRLAMCNEo8eH1LqcOppkWYP5ZN6mOftjvhs134NjUdlRYrpnz9JwpKTWgfHYSZozvU+9wqhRxTh7QBAHy08ST05VeuPP/wjxPILzGiZZgf7uvdst7vFxagwVcP9UJChD+y9BUY+f4WfLcnAzIZ8OD18Vg9tR/6JDh/I0MiIncZ2SkGMhmw+0wRMoqcs/hmU8YEpRZCCLx3YXjkvt4t6rUCqTsF+6nx5UPX4ZYuMTBbBab/cAD/+HAbUk8XIVCjxH/v6dbgFW9HdY5Bm6gAGCrM+HjzqVrbZRSVYeHmNADAjJvaNXh354hADb7+Zy+0CvcHALQK98d3j/TGv0e1h5+auzIQkXfTaX2QcmEvsp/2c5jnapig1OKPY3k4eE4PP7UCD/VrJXU4V6RRKjDvzi6YckNrAMD+jKrFz968oxNaXvhl3xAKuQzTbqzqRfl0SxoKainsmrP6GExmK3q1CsXQ9o3baDAyyAfLJvXBgnu7YdWT/dCjJbcoJ6Km45YuVbN5VnI2z1UxQamBEMJeXDq+VwuEOnGjPleRyWR4emgS5tzeCaH+akwdkojhydGNPu+wDjokNwtCqcmCBRtPVnv+z7NFWLk/EzJZ1aJszli5NdhPjeHJ0dw1mIianBHJOqgUMhzJMuB4Tt3Wf7pWMUGpwebj+diXfh4+KrnH955cbmzPOOx5YYi9fqSxbIkPAHyx/QxyLpnSLITAqxemFf+jWyySm1VfnZaIiC4K9lOjf2LVLET2olwZE5TLXFp7ck9KC0QEaiSOqP6cvf/MwDYR6NEiBEaz1b6iLgD8dCALf549Dz+1As8MS3LqexIRNVW2NVFW7s+s97Yl1xImKJfZfqoAu88UQa2U45H+3tV74iqX9qIsTT2L9MIyVFRa8MavVXv7PDogAVFBXGaeiKgubmwfBV+VAmcKyuw1g1QdE5TL2HpP7u4Zh0j+0rXrnRCGvq3DUWmp6mH6ZEsazp0vR7TWB//0smEwIiIp+amVuPHChAKuiVI7JiiX2HmqADtOFUKtkOPRgQlSh+Nxnh5aVdfyw58Z+OD3qqGe6cOT4KtmMSsRUX3YFm37+UBmnTd+vdYwQblE68gAPDYwAROub4lora/U4Xicrs1DMKRdJKwCKDNZ0DlWi1subIBFRER1179NBLS+KuQWG7HzVIHU4XgkJiiXCAvQ4F/D2+K5m2rfhfda99SNF2cHvTCyPeRy5xbkEhFdC9RKOW7qWLUTO2fz1IwJCtVLhxgt/ntPN7x3d1f05CJqREQNNurCMM+qg1kwmi0SR+N5JE1Q/vvf/yI+Ph4+Pj7o3r07Nm/eLGU4VEc3dYy2j58SEVHDpMSHITJQA0OFGZv+zr/6C64xkiUo33zzDaZOnYrnn38ee/fuRb9+/TBixAicPXtWqpCIiIjcRiGX2XtROMxTnUxItEpMSkoKunXrhg8//NB+rF27drj11lsxe/bsK77WYDBAq9VCr9cjKCjI1aESERG5xP7087jlg63wUclxZ484CABCAALiwn+rvobt6xqeE6j6QgCwikufE7jw0ouvudK5L3mNVQAxWh+8fnsnp15vfX5/S7JFrMlkwp49e/B///d/DseHDh2Kbdu2VWtvNBphNF7cqM5gMLg8RiIiIlfrFKtFq3B/nMovxefbz0gdjoNWEQ3fbNYZJElQ8vPzYbFYEBXluPNtVFQUsrOzq7WfPXs2Xn75ZXeFR0RE5BYymQwf3NMNqw5mQQhAJgNkF45X/b/skmMXtzKp8Tnb1zLZJccuPVfVwWrtL/kaMkB+oU2gjyQpgp2k7375njFCiBr3kZkxYwamTZtm/9pgMCAuLs7l8REREblau+ggtItmucLlJElQwsPDoVAoqvWW5ObmVutVAQCNRgONxvs27SMiIqKGkWQWj1qtRvfu3bFu3TqH4+vWrUOfPn2kCImIiIg8iGRDPNOmTcP48ePRo0cP9O7dG//73/9w9uxZPProo1KFRERERB5CsgTlzjvvREFBAf7zn/8gKysLycnJWLVqFVq0aCFVSEREROQhJFsHpTG4DgoREZH3qc/vb+7FQ0RERB6HCQoRERF5HCYoRERE5HGYoBAREZHHYYJCREREHocJChEREXkcJihERETkcZigEBERkceRdi/lBrKtLWcwGCSOhIiIiOrK9nu7LmvEemWCUlxcDACIi4uTOBIiIiKqr+LiYmi12iu28cql7q1WKzIzMxEYGAiZTCZ1OPViMBgQFxeH9PT0a2aZfl4zr7mp4jXzmpsqV12zEALFxcWIiYmBXH7lKhOv7EGRy+WIjY2VOoxGCQoKumZ+0G14zdcGXvO1gdd8bXDFNV+t58SGRbJERETkcZigEBERkcdhguJmGo0GL730EjQajdShuA2v+drAa7428JqvDZ5wzV5ZJEtERERNG3tQiIiIyOMwQSEiIiKPwwSFiIiIPA4TFCIiIvI4TFCIiIjI4zBBaYBNmzZh1KhRiImJgUwmw4oVKxyez8nJwYQJExATEwM/Pz8MHz4cx48fd2iTnZ2N8ePHQ6fTwd/fH926dcP333/v0KZly5aQyWQOj//7v/9z9eXVyBnXfPLkSdx2222IiIhAUFAQxo4di5ycHIc2RUVFGD9+PLRaLbRaLcaPH4/z58+7+Opq5q5r9pT7PHv2bPTs2ROBgYGIjIzErbfeimPHjjm0EUJg5syZiImJga+vLwYOHIjDhw87tDEajZgyZQrCw8Ph7++P0aNHIyMjw6GNp9xnd15zU7vP//vf/zBw4EAEBQVBJpPVeP+a2n2uyzU3pftcWFiIKVOmICkpCX5+fmjevDmeeOIJ6PV6h/O46j4zQWmA0tJSdO7cGfPnz6/2nBACt956K06dOoUff/wRe/fuRYsWLTBkyBCUlpba240fPx7Hjh3DypUrcfDgQYwZMwZ33nkn9u7d63C+//znP8jKyrI/XnjhBZdfX00ae82lpaUYOnQoZDIZNmzYgK1bt8JkMmHUqFGwWq32c40bNw779u3D6tWrsXr1auzbtw/jx49323Veyl3XDHjGfd64cSMef/xx7NixA+vWrYPZbMbQoUMdfm7nzJmDt99+G/Pnz0dqaip0Oh1uvPFG+waeADB16lQsX74cS5cuxZYtW1BSUoKRI0fCYrHY23jKfXbnNQNN6z6XlZVh+PDheO6552p9r6Z2n+tyzUDTuc+ZmZnIzMzEW2+9hYMHD2LRokVYvXo1Jk6c6PBeLrvPghoFgFi+fLn962PHjgkA4tChQ/ZjZrNZhIaGioULF9qP+fv7iy+++MLhXKGhoeLjjz+2f92iRQvxzjvvuCz2hmrINa9Zs0bI5XKh1+vtbQoLCwUAsW7dOiGEEH/99ZcAIHbs2GFvs337dgFAHD161MVXdWWuumYhPPc+5+bmCgBi48aNQgghrFar0Ol04vXXX7e3qaioEFqtVixYsEAIIcT58+eFSqUSS5cutbc5d+6ckMvlYvXq1UIIz77PrrpmIZrWfb7U77//LgCIoqIih+NN7T5fqrZrFqLp3mebb7/9VqjValFZWSmEcO19Zg+KkxmNRgCAj4+P/ZhCoYBarcaWLVvsx/r27YtvvvkGhYWFsFqtWLp0KYxGIwYOHOhwvjfeeANhYWHo0qULXnvtNZhMJrdcR33U5ZqNRiNkMpnDqoQ+Pj6Qy+X2Ntu3b4dWq0VKSoq9Ta9evaDVarFt2zZ3XEqdOeuabTzxPtu6cUNDQwEAaWlpyM7OxtChQ+1tNBoNBgwYYL8/e/bsQWVlpUObmJgYJCcn29t48n121TXbNJX7XBdN7T7XR1O+z3q9HkFBQVAqq/YaduV9ZoLiZG3btkWLFi0wY8YMFBUVwWQy4fXXX0d2djaysrLs7b755huYzWaEhYVBo9HgkUcewfLly5GQkGBv8+STT2Lp0qX4/fffMXnyZMybNw+TJk2S4rKuqC7X3KtXL/j7++Nf//oXysrKUFpaimeffRZWq9XeJjs7G5GRkdXOHxkZiezsbLde09U465oBz7zPQghMmzYNffv2RXJyMgDY70FUVJRD26ioKPtz2dnZUKvVCAkJuWIbT7zPrrxmoGnd57poave5rpryfS4oKMArr7yCRx55xH7MlfdZ2ahXUzUqlQo//PADJk6ciNDQUCgUCgwZMgQjRoxwaPfCCy+gqKgI69evR3h4OFasWIE77rgDmzdvRseOHQEATz31lL19p06dEBISgn/84x/27NxT1OWaIyIi8N133+Gxxx7De++9B7lcjrvvvhvdunWDQqGwt5PJZNXOL4So8biUnHnNnnifJ0+ejAMHDlTr6QGq36O63J/L23jifXb1NV8L9/lq52joeZzJ1dfcVO+zwWDAzTffjPbt2+Oll1664jmudJ76YILiAt27d8e+ffug1+thMpkQERGBlJQU9OjRA0DVzI758+fj0KFD6NChAwCgc+fO2Lx5Mz744AMsWLCgxvP26tULAHDixAmPSlCAq18zAAwdOhQnT55Efn4+lEolgoODodPpEB8fDwDQ6XTVZrgAQF5eXrUs3xM445prIvV9njJlClauXIlNmzYhNjbWflyn0wGo+ospOjrafjw3N9d+f3Q6HUwmE4qKihx6FHJzc9GnTx97G0+7z66+5pp4832ui6Z2nxuqKdzn4uJiDB8+HAEBAVi+fDlUKpXDeVx1nznE40JarRYRERE4fvw4du/ejVtuuQVAVSU4AMjljt9+hUJRbXbHpWwzfC79YfI0tV3zpcLDwxEcHIwNGzYgNzcXo0ePBgD07t0ber0eu3btsrfduXMn9Hr9FT/opdaYa66JVPdZCIHJkydj2bJl2LBhQ7UkKj4+HjqdDuvWrbMfM5lM2Lhxo/3+dO/eHSqVyqFNVlYWDh06ZG/jSffZXddcE2++z3XR1O5zQ3n7fTYYDBg6dCjUajVWrlzpUHcHuPg+N6rE9hpVXFws9u7dK/bu3SsAiLffflvs3btXnDlzRghRVeX8+++/i5MnT4oVK1aIFi1aiDFjxthfbzKZROvWrUW/fv3Ezp07xYkTJ8Rbb70lZDKZ+OWXX4QQQmzbts1+3lOnTolvvvlGxMTEiNGjR3vlNQshxKeffiq2b98uTpw4Ib788ksRGhoqpk2b5tBm+PDholOnTmL79u1i+/btomPHjmLkyJFuu85LueOaPek+P/bYY0Kr1Yo//vhDZGVl2R9lZWX2Nq+//rrQarVi2bJl4uDBg+Luu+8W0dHRwmAw2Ns8+uijIjY2Vqxfv178+eef4oYbbhCdO3cWZrPZ3sZT7rO7rrkp3uesrCyxd+9esXDhQgFAbNq0Sezdu1cUFBTY2zS1+3y1a25q99lgMIiUlBTRsWNHceLECYfzuOPfMxOUBrBNMbv8cf/99wshhHj33XdFbGysUKlUonnz5uKFF14QRqPR4Rx///23GDNmjIiMjBR+fn6iU6dODtOO9+zZI1JSUoRWqxU+Pj4iKSlJvPTSS6K0tNSdl2rnjGv+17/+JaKiooRKpRKJiYli7ty5wmq1OrQpKCgQ99xzjwgMDBSBgYHinnvuqXEqnzu445o96T7XdK0AxGeffWZvY7VaxUsvvSR0Op3QaDSif//+4uDBgw7nKS8vF5MnTxahoaHC19dXjBw5Upw9e9ahjafcZ3ddc1O8zy+99NJVz9PU7vPVrrmp3efaPgMBiLS0NHs7V91n2YULISIiIvIYrEEhIiIij8MEhYiIiDwOExQiIiLyOExQiIiIyOMwQSEiIiKPwwSFiIiIPA4TFCIiIvI4TFCIiIjI4zBBISIiIo/DBIWIiIg8DhMUIiIi8jj/D6kKanWeob/6AAAAAElFTkSuQmCC"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=5c8941ed-945f-490d-bf70-ff6451c3e319">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">genre_sales</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">'Genre'</span><span class="p">)[</span><span class="s1">'Global_Sales'</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">ascending</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">5</span><span class="p">))</span>

<span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">genre_sales</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">genre_sales</span><span class="o">.</span><span class="n">values</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">"Global Video Game Sales by Genre"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">"Genre"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">"Global Sales (Millions)"</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">rotation</span><span class="o">=</span><span class="mi">45</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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hw8farTz9fVFiRIlcPjwYVSoUAEmJibIly8fRo8enWJktJ9//hlFihSBiYkJChQogKlTp2LZsmUQEdy7d0/jNdMyGmFyZcuWhYhgxowZqc5P7TUfPXqE5s2bI1euXMidOzeaN2+OkydPpjqc+Z9//olWrVrBzs4ORkZGcHBwQK1atbBw4UKNdleuXEHDhg1hYWEBY2NjlC5d+l+HRk/uw4cPmDt3LqpWrYq8efPC0NAQVlZWqFatGqZPn47nz59rtE/re+rq6ooGDRqk+PcklSH61SP9zZw584veg49dv34dQ4YMQYUKFWBrawtDQ0NYWlrC19cXK1eu1Gj78uVLBAUFwc7ODmZmZqhatSqOHTuW4vNLbTRC9fRu3bohf/78MDIygq2tLXx8fDB58mSlzffffw8fHx/Y2NjA2NgYLi4uCAoKwv379z+7HOrRCFeuXIkBAwbA1tYWJiYmqFatGs6fP5/qc2JiYmBiYoJ69ep99rVTk57fMJC2z0c9GuG5c+dSXbZDhw4p0z71nQGAyMhIDBgwAO7u7jAyMoKVlRXKly+PMWPG4M2bN+leViLSTyrgC+6USURERJQBduzYIY0aNZJdu3YpA3UQEWUVDFtERET01V2/fl3CwsJk4MCBYm5uLhcvXkx1sAkiIn3God+JiIjoq+vTp480atRILC0tZc2aNQxaRJQl8cwWERERERGRFvDMFhERERERkRYwbBEREREREWkBwxYREREREZEW8KbGaZSYmCiPHz+W3Llz8yJeIiIiIqJsDIC8fv1aHB0dJUeOT5+/YthKo8ePH4uzs7OuyyAiIiIiokzi4cOH4uTk9Mn5DFtplDt3bhFJekPz5Mmj42qIiIiIiEhXoqOjxdnZWckIn8KwlUbqroN58uRh2CIiIiIion+9vIgDZBAREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFhjqugD6Mm4jd+m6hP/k/rQGui6BiIiIiEireGaLiIiIiIhICxi2iIiIiIiItIBhi4iIiIiISAsYtoiIiIiIiLSAYYuIiIiIiEgLGLaIiIiIiIi0gGGLiIiIiIhICxi2iIiIiIiItIBhi4iIiIiISAsYtoiIiIiIiLSAYYuIiIiIiEgLGLaIiIiIiIi0gGGLiIiIiIhIC3Qato4ePSoNGzYUR0dHUalUsnXrVmVeXFycjBgxQkqWLCnm5ubi6OgonTp1ksePH2u8RkxMjPTv319sbGzE3NxcGjVqJI8ePdJo8/LlS+nYsaNYWFiIhYWFdOzYUV69evUVlpCIiIiIiLIrnYatt2/fSunSpWXevHkp5r17904uXrwoY8eOlYsXL8rmzZvl9u3b0qhRI412gwYNki1btsjatWvl+PHj8ubNGwkMDJSEhASlTbt27eTSpUuyZ88e2bNnj1y6dEk6duyo9eUjIiIiIqLsSwUAui5CRESlUsmWLVukSZMmn2xz7tw5qVSpkoSFhYmLi4tERUWJra2trFy5Ulq3bi0iIo8fPxZnZ2fZvXu3+Pv7y40bN6R48eJy+vRp8fLyEhGR06dPS+XKleXmzZtSpEiRNNUXHR0tFhYWEhUVJXny5PnPy/tfuY3cpesS/pP70xrougQiIiIioi+S1mygV9dsRUVFiUqlkrx584qIyIULFyQuLk7q1q2rtHF0dBRPT085efKkiIicOnVKLCwslKAlIuLt7S0WFhZKGyIiIiIiooxmqOsC0urDhw8ycuRIadeunZIew8PDxdjYWCwtLTXa2tvbS3h4uNLGzs4uxevZ2dkpbVITExMjMTExyuPo6OiMWAwiIiIiIsom9OLMVlxcnLRp00YSExPlp59++tf2AESlUimPk///p9p8bOrUqcqAGhYWFuLs7PxlxRMRERERUbaU6cNWXFyctGrVSu7duyf79u3T6BPp4OAgsbGx8vLlS43nREREiL29vdLm6dOnKV43MjJSaZOaUaNGSVRUlPL38OHDDFoiIiIiIiLKDjJ12FIHrTt37sj+/fvF2tpaY3758uXFyMhI9u3bp0x78uSJXL16VXx8fEREpHLlyhIVFSVnz55V2pw5c0aioqKUNqkxMTGRPHnyaPwRERERERGllU6v2Xrz5o3cvXtXeXzv3j25dOmSWFlZiaOjo7Ro0UIuXrwoO3fulISEBOUaKysrKzE2NhYLCwsJCgqSIUOGiLW1tVhZWcnQoUOlZMmSUqdOHRERKVasmNSrV0+6d+8uixYtEhGRHj16SGBgYJpHIiQiIiIiIkovnYat8+fPS82aNZXHwcHBIiLSuXNnmTBhgmzfvl1ERMqUKaPxvEOHDkmNGjVERGT27NliaGgorVq1kvfv30vt2rVl+fLlYmBgoLT/7bffZMCAAcqohY0aNUr13l5EREREREQZJdPcZyuz4322Mhbvs0VERERE+ipL3meLiIiIiIhIXzBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEWMGwRERERERFpAcMWERERERGRFjBsERERERERaQHDFhERERERkRYwbBEREREREWkBwxYREREREZEW6DRsHT16VBo2bCiOjo6iUqlk69atGvMByIQJE8TR0VFy5swpNWrUkGvXrmm0iYmJkf79+4uNjY2Ym5tLo0aN5NGjRxptXr58KR07dhQLCwuxsLCQjh07yqtXr7S8dERERERElJ3pNGy9fftWSpcuLfPmzUt1/owZM2TWrFkyb948OXfunDg4OIifn5+8fv1aaTNo0CDZsmWLrF27Vo4fPy5v3ryRwMBASUhIUNq0a9dOLl26JHv27JE9e/bIpUuXpGPHjlpfPiIiIiIiyr5UAKDrIkREVCqVbNmyRZo0aSIiSWe1HB0dZdCgQTJixAgRSTqLZW9vL9OnT5eePXtKVFSU2NraysqVK6V169YiIvL48WNxdnaW3bt3i7+/v9y4cUOKFy8up0+fFi8vLxEROX36tFSuXFlu3rwpRYoUSVN90dHRYmFhIVFRUZInT56MfwPSyW3kLl2X8J/cn9ZA1yUQEREREX2RtGYDw69YU7rcu3dPwsPDpW7duso0ExMT8fX1lZMnT0rPnj3lwoULEhcXp9HG0dFRPD095eTJk+Lv7y+nTp0SCwsLJWiJiHh7e4uFhYWcPHkyzWGLdEufwyWDJREREVH2lGnDVnh4uIiI2Nvba0y3t7eXsLAwpY2xsbFYWlqmaKN+fnh4uNjZ2aV4fTs7O6VNamJiYiQmJkZ5HB0d/WULQkRERERE2VKmH41QpVJpPAaQYtrHPm6TWvt/e52pU6cqA2pYWFiIs7NzOisnIiIiIqLsLNOGLQcHBxGRFGefIiIilLNdDg4OEhsbKy9fvvxsm6dPn6Z4/cjIyBRnzZIbNWqUREVFKX8PHz78T8tDRERERETZS6YNW+7u7uLg4CD79u1TpsXGxsqRI0fEx8dHRETKly8vRkZGGm2ePHkiV69eVdpUrlxZoqKi5OzZs0qbM2fOSFRUlNImNSYmJpInTx6NPyIiIiIiorTS6TVbb968kbt37yqP7927J5cuXRIrKytxcXGRQYMGSUhIiHh4eIiHh4eEhISImZmZtGvXTkRELCwsJCgoSIYMGSLW1tZiZWUlQ4cOlZIlS0qdOnVERKRYsWJSr1496d69uyxatEhERHr06CGBgYEcHIOIiIiIiLRGp2Hr/PnzUrNmTeVxcHCwiIh07txZli9fLsOHD5f3799Lnz595OXLl+Ll5SV79+6V3LlzK8+ZPXu2GBoaSqtWreT9+/dSu3ZtWb58uRgYGChtfvvtNxkwYIAyamGjRo0+eW8vIiIiIiKijJBp7rOV2fE+WxkrvcOh6/Pycuh3IiIioqwlrdkg016zRUREREREpM8YtoiIiIiIiLSAYYuIiIiIiEgLGLaIiIiIiIi0gGGLiIiIiIhICxi2iIiIiIiItIBhi4iIiIiISAsYtoiIiIiIiLSAYYuIiIiIiEgLGLaIiIiIiIi0gGGLiIiIiIhICxi2iIiIiIiItIBhi4iIiIiISAsYtoiIiIiIiLSAYYuIiIiIiEgLGLaIiIiIiIi0wDA9jQHIkSNH5NixY3L//n159+6d2NraStmyZaVOnTri7OysrTqJiIiIiIj0SprObL1//15CQkLE2dlZ6tevL7t27ZJXr16JgYGB3L17V8aPHy/u7u4SEBAgp0+f1nbNREREREREmV6azmwVLlxYvLy8ZOHCheLv7y9GRkYp2oSFhcnq1auldevW8u2330r37t0zvFgiIiIiIiJ9kaaw9fvvv4unp+dn27i6usqoUaNkyJAhEhYWliHFERERERER6as0dSP8t6CVnLGxsXh4eHxxQURERERERFlBukcj3LNnjxw/flx5PH/+fClTpoy0a9dOXr58maHFERERERER6at0h61hw4ZJdHS0iIhcuXJFhgwZIgEBAfL3339LcHBwhhdIRERERESkj9I19LuIyL1796R48eIiIrJp0yYJDAyUkJAQuXjxogQEBGR4gURERERERPoo3We2jI2N5d27dyIisn//fqlbt66IiFhZWSlnvIiIiIiIiLK7dJ/Zqlq1qgQHB0uVKlXk7Nmzsm7dOhERuX37tjg5OWV4gURERERERPoo3We25s2bJ4aGhrJx40ZZsGCB5M+fX0SShoevV69ehhdIRERERESkj9J9ZsvFxUV27tyZYvrs2bMzpCAiIiIiIqKsIN1hS0QkMTFR7t69KxEREZKYmKgxr3r16hlSGBERERERkT5Ld9g6ffq0tGvXTsLCwgSAxjyVSiUJCQkZVhwREREREZG+SnfY6tWrl1SoUEF27dol+fLlE5VKpY26iIiIiIiI9Fq6w9adO3dk48aNUqhQIW3UQ0RERERElCWkezRCLy8vuXv3rjZqISIiIiIiyjLSfWarf//+MmTIEAkPD5eSJUuKkZGRxvxSpUplWHFERERERET6Kt1hq3nz5iIi0q1bN2WaSqUSABwgg4iIiIiI6P9Ld9i6d++eNuogIiIiIiLKUtIdtlxdXbVRBxERERERUZbyRTc1/uuvv2TOnDly48YNUalUUqxYMRk4cKAULFgwo+sjIiIiIiLSS+kejTA0NFSKFy8uZ8+elVKlSomnp6ecOXNGSpQoIfv27dNGjURERERERHon3We2Ro4cKYMHD5Zp06almD5ixAjx8/PLsOKIiIiIiIj0VbrPbN24cUOCgoJSTO/WrZtcv349Q4oiIiIiIiLSd+kOW7a2tnLp0qUU0y9duiR2dnYZURMREREREZHeS3c3wu7du0uPHj3k77//Fh8fH1GpVHL8+HGZPn26DBkyRBs1EhERERER6Z10h62xY8dK7ty55fvvv5dRo0aJiIijo6NMmDBBBgwYkOEFEhERERER6aN0hy2VSiWDBw+WwYMHy+vXr0VEJHfu3BleGBERERERkT77ovtsqTFkERERERERpS5NYatcuXJy4MABsbS0lLJly4pKpfpk24sXL2ZYcURERERERPoqTWGrcePGYmJiIiIiTZo00WY9GuLj42XChAny22+/SXh4uOTLl0+6dOki3377reTIkTSQIgCZOHGiLF68WF6+fCleXl4yf/58KVGihPI6MTExMnToUFmzZo28f/9eateuLT/99JM4OTl9tWUhIiIiIqLsJU1ha/z48an+v7ZNnz5dFi5cKCtWrJASJUrI+fPnpWvXrmJhYSEDBw4UEZEZM2bIrFmzZPny5VK4cGGZPHmy+Pn5ya1bt5RujoMGDZIdO3bI2rVrxdraWoYMGSKBgYFy4cIFMTAw+GrLQ0RERERE2cd/umZL206dOiWNGzeWBg0aiIiIm5ubrFmzRs6fPy8iSWe15syZI2PGjJFmzZqJiMiKFSvE3t5eVq9eLT179pSoqChZtmyZrFy5UurUqSMiIqtWrRJnZ2fZv3+/+Pv762bhiIiIiIgoS0vTTY0tLS3FysoqTX8ZqWrVqnLgwAG5ffu2iIj8+eefcvz4cQkICBARkXv37kl4eLjUrVtXeY6JiYn4+vrKyZMnRUTkwoULEhcXp9HG0dFRPD09lTZEREREREQZLU1ntubMmaPlMlI3YsQIiYqKkqJFi4qBgYEkJCTIlClTpG3btiIiEh4eLiIi9vb2Gs+zt7eXsLAwpY2xsbFYWlqmaKN+fmpiYmIkJiZGeRwdHZ0hy0RERERERNlDmsJW586dtV1HqtatWyerVq2S1atXS4kSJeTSpUsyaNAgcXR01Kjp49ERAXx2xMS0tJk6dapMnDjxvy0AERERERFlW2kKW+k5q5MnT54vLuZjw4YNk5EjR0qbNm1ERKRkyZISFhYmU6dOlc6dO4uDg4OIiDJSoVpERIRytsvBwUFiY2Pl5cuXGme3IiIixMfH55P/9qhRoyQ4OFh5HB0dLc7Ozhm2bERERERElLWl6ZqtvHnziqWl5Wf/1G0y0rt375Qh3tUMDAwkMTFRRETc3d3FwcFB9u3bp8yPjY2VI0eOKEGqfPnyYmRkpNHmyZMncvXq1c+GLRMTE8mTJ4/GHxERERERUVql6czWoUOHtF1Hqho2bChTpkwRFxcXKVGihPzxxx8ya9Ys6datm4gkdR8cNGiQhISEiIeHh3h4eEhISIiYmZlJu3btRETEwsJCgoKCZMiQIWJtbS1WVlYydOhQKVmypDI6IRERERERUUZLU9jy9fXVdh2pmjt3rowdO1b69OkjERER4ujoKD179pRx48YpbYYPHy7v37+XPn36KDc13rt3r3KPLRGR2bNni6GhobRq1Uq5qfHy5ct5jy0iIiIiItIaFQD8W6PLly+Lp6en5MiRQy5fvvzZtqVKlcqw4jKT6OhosbCwkKioqEzRpdBt5C5dl/Cf3J/WIF3t9Xl507usRERERJS5pTUbpOnMVpkyZSQ8PFzs7OykTJkyolKpJLWMplKpJCEh4curJiIiIiIiyiLSFLbu3bsntra2yv8TERERERHR56UpbLm6uqb6/0RERERERJS6NIUtEZGjR4+mqV316tW/uBgiIiIiIqKsIs1hq0aNGqJSqUREUr1eS4TXbBEREREREamlOWxZWlpK7ty5pUuXLtKxY0exsbHRZl1ERERERER6LUdaGz558kSmT58up06dkpIlS0pQUJCcPHlS8uTJIxYWFsofERERERERpSNsGRsbS+vWrSU0NFRu3bolpUqVkn79+omzs7OMGTNG4uPjtVknERERERGRXklz2ErO2dlZxo0bJ/v375fChQvLtGnTJDo6OqNrIyIiIiIi0lvpDlsxMTGyevVqqVOnjnh6eoqNjY3s2rVLrKystFEfERERERGRXkrzABlnz56VX375RdauXSvu7u7SpUsXWb9+PUMWERERERFRKtIctry9vcXFxUUGDBgg5cuXFxGR48ePp2jXqFGjjKuOiIiIiIhIT6U5bImIPHjwQCZNmvTJ+bzPFhERERERUZI0h63ExERt1kFERERERJSlfNFohERERERERPR5aQpbp06dSvMLvn37Vq5du/bFBREREREREWUFaQpbnTp1Ej8/P1m/fr28efMm1TbXr1+X0aNHS6FCheTixYsZWiQREREREZG+SdM1W9evX5dFixbJuHHjpH379lK4cGFxdHQUU1NTefnypdy8eVPevn0rzZo1k3379omnp6e26yYiIiIiIsrU0hS2jIyMpF+/ftKvXz+5ePGiHDt2TO7fvy/v37+X0qVLy+DBg6VmzZq85xYREREREdH/l66h30VEypUrJ+XKldNGLURERERE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rGTo0KFSsmRJZXRCIiIiIiKijJbmsPXs2TNxcnJSHh86dEgaNmyoPK5Ro4YMGTIkQ4urWLGibNmyRUaNGiXfffeduLu7y5w5c6R9+/ZKm+HDh8v79++lT58+8vLlS/Hy8pK9e/dK7ty5lTazZ88WQ0NDadWqlbx//15q164ty5cvFwMDgwytl4iIiIiISC3NYcvKykqePHkizs7OkpiYKOfPn5fBgwcr82NjYwVAhhcYGBgogYGBn5yvUqlkwoQJMmHChE+2MTU1lblz58rcuXMzvD4iIiIiIqLUpPmaLV9fX5k0aZI8fPhQ5syZI4mJiVKzZk1l/vXr1zVuOExERERERJSdpfnM1pQpU8TPz0/c3NwkR44c8uOPP4q5ubkyf+XKlVKrVi2tFElERERERKRv0hy23N3d5caNG3L9+nWxtbUVR0dHjfkTJ07UuKaLiIiIiIgoO0vXTY2NjIykdOnSqc771HQiIiIiIqLsKM3XbBEREREREVHaMWwRERERERFpAcMWERERERGRFjBsERERERERaUGaBsi4fPlyml+wVKlSX1wMERERERFRVpGmsFWmTBlRqVQCINX56nkqlUoSEhIytEAiIiIiIiJ9lKawde/ePW3XQUREWZDbyF26LuGL3Z/WQNclEBGRnktT2HJ1ddV2HURERERERFlKum5qnNz169flwYMHEhsbqzG9UaNG/7koIiIiIiIifZfusPX3339L06ZN5cqVKxrXcalUKhERXrNFREREREQkXxC2Bg4cKO7u7rJ//34pUKCAnD17Vp4/fy5DhgyR//3vf9qokYiIKNPT5+vTRHiNGhGRNqQ7bJ06dUoOHjwotra2kiNHDsmRI4dUrVpVpk6dKgMGDJA//vhDG3USERERERHplXTf1DghIUFy5colIiI2Njby+PFjEUkaROPWrVsZWx0REREREZGeSveZLU9PT7l8+bIUKFBAvLy8ZMaMGWJsbCyLFy+WAgUKaKNGIiIiIiIivZPusPXtt9/K27dvRURk8uTJEhgYKNWqVRNra2tZt25dhhdIRERERESkj9Idtvz9/ZX/L1CggFy/fl1evHghlpaWyoiERERERERE2d0X32dLROThw4eiUqnEyckpo+ohIiIiIiLKEtI9QEZ8fLyMHTtWLCwsxM3NTVxdXcXCwkK+/fZbiYuL00aNREREREREeifdZ7b69esnW7ZskRkzZkjlypVFJGk4+AkTJsizZ89k4cKFGV4kERERERGRvkl32FqzZo2sXbtW6tevr0wrVaqUuLi4SJs2bRi2iIiIiIiI5Au6EZqamoqbm1uK6W5ubmJsbJwRNREREREREem9dIetvn37yqRJkyQmJkaZFhMTI1OmTJF+/fplaHFERERERET6Kk3dCJs1a6bxeP/+/eLk5CSlS5cWEZE///xTYmNjpXbt2hlfIRERERERkR5KU9iysLDQeNy8eXONx87OzhlXERERERERURaQprD1yy+/aLsOIiIiIiKiLOWLb2ocGRkpt27dEpVKJYULFxZbW9uMrIuIiIiIiEivpXuAjLdv30q3bt0kX758Ur16dalWrZo4OjpKUFCQvHv3Ths1EhERERER6Z10h63g4GA5cuSI7NixQ169eiWvXr2Sbdu2yZEjR2TIkCHaqJGIiIiIiEjvpLsb4aZNm2Tjxo1So0YNZVpAQIDkzJlTWrVqJQsWLMjI+oiIiIiIiPRSus9svXv3Tuzt7VNMt7OzYzdCIiIiIiKi/y/dYaty5coyfvx4+fDhgzLt/fv3MnHiRKlcuXKGFkdERERERKSv0t2N8IcffpB69eopNzVWqVRy6dIlMTU1ldDQUG3USEREREREpHfSHbY8PT3lzp07smrVKrl586YAkDZt2kj79u0lZ86c2qiRiIiIiIhI73zRfbZy5swp3bt3z+haiIiIiIiIsow0ha3t27en+QUbNWr0xcUQERERERFlFWkKW02aNEnTi6lUKklISPgv9RAREREREWUJaQpbiYmJ2q6DiIiIiIgoS0n30O9ERERERET079I8QMb79+/lwIEDEhgYKCIio0aNkpiYGGW+gYGBTJo0SUxNTTO+SiIiIiIiIj2T5rD166+/ys6dO5WwNW/ePClRooQy3PvNmzfF0dFRBg8erJ1KiYiIiIiI9EiauxH+9ttv0q1bN41pq1evlkOHDsmhQ4dk5syZsn79+gwvkIiIiIiISB+lOWzdvn1bChcurDw2NTWVHDn+7+mVKlWS69evZ2x1REREREREeirN3QijoqLE0PD/mkdGRmrMT0xM1LiGi4iIiIiIKDtL85ktJycnuXr16ifnX758WZycnDKkqE+ZOnWqqFQqGTRokDINgEyYMEEcHR0lZ86cUqNGDbl27ZrG82JiYqR/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UylfvrwcO3ZM1yUREREREVEWlW3C1rp162TQoEEyZswY+eOPP6RatWpSv359efDgga5LIyIiIiKiLCjbhK1Zs2ZJUFCQfPPNN1KsWDGZM2eOODs7y4IFC3RdGhERERERZUGGui7ga4iNjZULFy7IyJEjNabXrVtXTp48mepzYmJiJCYmRnkcFRUlIiLR0dHaKzQdEmPe6bqE/yS976M+L292WlYRLu+/4fLqj+y0rCJc3n+jz8ubnZZVhMv7b7Lb8mqLug4An22nwr+1yAIeP34s+fPnlxMnToiPj48yPSQkRFasWCG3bt1K8ZwJEybIxIkTv2aZRERERESkRx4+fChOTk6fnJ8tzmypqVQqjccAUkxTGzVqlAQHByuPExMT5cWLF2Jtbf3J52QV0dHR4uzsLA8fPpQ8efLouhyty07Lm52WVYTLm5Vlp2UV4fJmddlpebPTsopwebMyAPL69WtxdHT8bLtsEbZsbGzEwMBAwsPDNaZHRESIvb19qs8xMTERExMTjWl58+bVVomZUp48ebL8DyW57LS82WlZRbi8WVl2WlYRLm9Wl52WNzstqwiXN6uysLD41zbZYoAMY2NjKV++vOzbt09j+r59+zS6FRIREREREWWUbHFmS0QkODhYOnbsKBUqVJDKlSvL4sWL5cGDB9KrVy9dl0ZERERERFlQtglbrVu3lufPn8t3330nT548EU9PT9m9e7e4urrqurRMx8TERMaPH5+iG2VWlZ2WNzstqwiXNyvLTssqwuXN6rLT8manZRXh8lI2GY2QiIiIiIjoa8sW12wRERERERF9bQxbREREREREWsCwRUREREREpAUMW0RERERERFrAsEVERERERKQFDFtEacSBO4lIH6nXXW/evNFxJUREn5aYmKjrErSCYYsoDRITE0WlUomIyK1bt+TVq1e6LYgojdQ72gkJCRqPs5OPN+BZdYP+KSqVStauXSsDBw6UZ8+e6bocrcpuny0lyY7rtawoR46kWLJ+/fos9Vtm2KJ0y24rtcTERGUFMHbsWOnbt6+cOXNGYmJidFxZ5pOVVo4i+v9dByAqlUqOHz8u8+bNk2fPnikHDbILABobcJGkDXpW+66mRv39ffbsmYwePVrKli0rNjY2Oq5Ku9Sf9Y0bN3Rcie6oP/eHDx9KZGSkREZG6rgi7VEv68frNX1fd2dnz58/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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=74db4537-3281-4ac7-a423-51ab6564e1f0">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [18]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">region_sales</span> <span class="o">=</span> <span class="n">df</span><span class="p">[[</span><span class="s1">'NA_Sales'</span><span class="p">,</span> <span class="s1">'EU_Sales'</span><span class="p">,</span> <span class="s1">'JP_Sales'</span><span class="p">,</span> <span class="s1">'Other_Sales'</span><span class="p">]]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
<span class="n">region_sales</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">7</span><span class="p">,</span><span class="mi">7</span><span class="p">))</span>

<span class="n">plt</span><span class="o">.</span><span class="n">pie</span><span class="p">(</span>
    <span class="n">region_sales</span><span class="o">.</span><span class="n">values</span><span class="p">,</span>
    <span class="n">labels</span><span class="o">=</span><span class="n">region_sales</span><span class="o">.</span><span class="n">index</span><span class="p">,</span>
    <span class="n">autopct</span><span class="o">=</span><span class="s1">'</span><span class="si">%1.1f%%</span><span class="s1">'</span><span class="p">,</span>
    <span class="n">startangle</span><span class="o">=</span><span class="mi">140</span>
<span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">"Global Video Game Sales by Region"</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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skRERESkB8sSERERkR4sS0RERER6sCwRERER6cGyRERERKQHyxIRERGRHixLRERERHqwLBERERHpwbJEREREpAfLEhEREZEeLEtEREREerAsEREREenBskRERESkB8sSERERkR4sS0RERER6sCwRERER6cGyRERERKQHyxIRERGRHixLRERERHqwLBERERHpwbJEREREpAfLEhEREZEeLEtEREREerAsEREREenBskRERESkB8sSERERkR4sS0RERER6sCwRERER6cGyRERERKQHyxIRERGRHixLRERERHqwLBERERHpwbJEREREpAfLEhEREZEeLEtEREREerAsEREREenBskRERESkB8sSERERkR4sS0RERER6sCwREdm48PBwvPfee6JjEJktliUiIhObOnUqhg8fXvL/MpkMMpkMdnZ2iIyMxJNPPonc3Nwq7euHH35A+/bt4e7uDldXVzRu3BiLFi0yYnoi26MUHYCIyNYNGDAA69atg1qtxv79+/HII48gNzcXn3zyid7H7d69G+PGjcOrr76KoUOHQiaT4fz58/j9999NlJzINvDIEhGRYA4ODggICEBISAjGjx+PCRMmYPPmzZU+btu2bejSpQueeuopNGjQAPXr18fw4cPx4Ycflmxz9epVDBs2DP7+/nBxcUHbtm2xe/duvfvNzMzEzJkz4efnBzc3N/Tq1QunTp0quf/UqVPo2bMnXF1d4ebmhtatW+Po0aM1/vyJzB3LEhGRmXF0dIRara50u4CAAJw7dw5nz56tcJucnBwMGjQIu3fvxokTJ9C/f38MGTIE8fHx5W4vSRIeeOABJCUlYceOHTh27BhatWqF3r17Iy0tDQAwYcIEBAcH48iRIzh27Bj+7//+D3Z2djX7ZIksAIfhiIjMyD///IMvv/wSvXv3rnTbRx99FPv370fTpk0RFhaGDh06oF+/fpgwYQIcHBwAAM2bN0fz5s1LHvPKK6/gp59+wpYtWzB//vwy+/zjjz9w5swZpKSklOzjrbfewubNm/H9999j5syZiI+Px1NPPYWGDRsCAOrVq2eIT53IbPHIEhGRYNu2bYOLiwtUKhU6duyIbt26lRpKq4izszO2b9+OmJgYPP/883BxccGiRYvQrl075OXlAQByc3Px9NNPo1GjRvDw8ICLiwsuXrxY4ZGlY8eOIScnB97e3nBx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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=37ae70e5-3ff3-4487-9f22-16c352cb8b55">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span> 
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=5e0d3a66-a423-44d5-80a9-f7dbfac5ae13">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span> 
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=09e4c908-9bd2-4442-b716-103065c702dc">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span> 
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs" id="cell-id=cc487cf7-1a44-44f2-a4e9-713369e6501d">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span> 
</pre></div>
</div>
</div>
</div>
</div>
</div>
</main>
</body>
</html>
