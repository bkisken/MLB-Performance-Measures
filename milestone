<!DOCTYPE html>

<html lang="en">
<head><meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Milestone1</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
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
<main>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><a href="https://github.com/bkisken/MLB-Performance-Measures.git">https://github.com/bkisken/MLB-Performance-Measures.git</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p>Group Members: Andrew Zimmerman, Brian Kisken</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="MLB-Increase-in-Performance-Over-the-Years"><strong>MLB Increase in Performance Over the Years</strong><a class="anchor-link" href="#MLB-Increase-in-Performance-Over-the-Years">¶</a></h1>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><strong>Collaboration Plan</strong></p>
<ol>
<li><p><strong>Collaboration Tools</strong>:</p>
<ul>
<li><strong>GitHub</strong>: We set up a private GitHub repository to coordinate and manage our code. All project files are stored here to ensure version control and collaboration.</li>
<li>We also have a shared google drive folder that contains notes and datasets, as well as a place for us to write down potential ideas for our project</li>
</ul>
</li>
<li><p><strong>Meeting Schedule</strong>:</p>
<ul>
<li>We will meet weekly to discuss progress, tasks, review the code, and plan our next steps.</li>
</ul>
</li>
<li><p><strong>Work Coordination</strong>:</p>
<ul>
<li>Tasks will be clearly divided between the two of us based on individual strengths</li>
</ul>
</li>
</ol>
<p>This plan helps us make sure both of us are involved in all aspects of the project.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><strong>Project Goal:</strong>
Our goal with this project is to explore how the performance of MLB players has evolved over the years. Specifically, we’ll look into how metrics like average pitch speed, hit velocity, and base-running speed have changed over time. We want to understand whether MLB players have consistently gotten faster and stronger, and if so, what might have driven these changes. We want to figure out if these changes are driven by certain factors and what impact they’ve had on the way the game is played today.</p>
<p><strong>Research Question:</strong>
Our main research question is: How has the performance of MLB players evolved over the years in terms of pitch speed, hit velocity, and base-running speed? We’ll also look at what factors could explain these changes. Are players getting faster and stronger due to improvements in training, technology, or other influences in the sport?</p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [118]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">string</span>
<span class="kn">import</span> <span class="nn">re</span>

<span class="n">pd</span><span class="o">.</span><span class="n">options</span><span class="o">.</span><span class="n">mode</span><span class="o">.</span><span class="n">copy_on_write</span> <span class="o">=</span> <span class="kc">True</span>
<span class="n">np</span><span class="o">.</span><span class="n">random</span><span class="o">.</span><span class="n">seed</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [119]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">google.colab</span> <span class="kn">import</span> <span class="n">drive</span>
<span class="n">drive</span><span class="o">.</span><span class="n">mount</span><span class="p">(</span><span class="s1">'/content/drive'</span><span class="p">)</span>
<span class="o">%</span><span class="n">cd</span> <span class="s2">"/content/drive/MyDrive/Colab Notebooks"</span>
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
<pre>Drive already mounted at /content/drive; to attempt to forcibly remount, call drive.mount("/content/drive", force_remount=True).
/content/drive/MyDrive/Colab Notebooks
</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [120]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1">#%%shell</span>
<span class="err">!</span><span class="n">jupyter</span> <span class="n">nbconvert</span> <span class="o">--</span><span class="n">to</span> <span class="n">html</span> <span class="s2">"Milestone1.ipynb"</span>
<span class="c1">#!ls</span>
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
<pre>[NbConvertApp] Converting notebook Milestone1.ipynb to html
[NbConvertApp] WARNING | Alternative text is missing on 3 image(s).
[NbConvertApp] Writing 523125 bytes to Milestone1.html
</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [121]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="o">%</span><span class="n">cd</span> <span class="n">MLB</span><span class="o">-</span><span class="n">Performance</span><span class="o">-</span><span class="n">Measures</span>
<span class="err">!</span><span class="n">ls</span>
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
<pre>/content/drive/MyDrive/Colab Notebooks/MLB-Performance-Measures
MLB-Performance-Measures  pitch_arsenals.csv  README.md
</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [122]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">pitches_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">'pitch_arsenals.csv'</span><span class="p">)</span>
<span class="n">pitches_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
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
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[122]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div class="colab-df-container" id="df-9f24c5f0-d89d-4548-ae95-4d48b44ddd86">
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
<th>last_name, first_name</th>
<th>pitcher</th>
<th>ff_avg_speed</th>
<th>si_avg_speed</th>
<th>fc_avg_speed</th>
<th>sl_avg_speed</th>
<th>ch_avg_speed</th>
<th>cu_avg_speed</th>
<th>fs_avg_speed</th>
<th>kn_avg_speed</th>
<th>st_avg_speed</th>
<th>sv_avg_speed</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>Burnes, Corbin</td>
<td>669203</td>
<td>96.4</td>
<td>96.3</td>
<td>95.0</td>
<td>88.2</td>
<td>90.3</td>
<td>81.7</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
</tr>
<tr>
<th>1</th>
<td>Cole, Gerrit</td>
<td>543037</td>
<td>97.8</td>
<td>98.6</td>
<td>92.0</td>
<td>88.7</td>
<td>89.7</td>
<td>83.0</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
</tr>
<tr>
<th>2</th>
<td>Alcantara, Sandy</td>
<td>645261</td>
<td>98.0</td>
<td>97.8</td>
<td>NaN</td>
<td>90.0</td>
<td>91.8</td>
<td>86.2</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
</tr>
<tr>
<th>3</th>
<td>Mikolas, Miles</td>
<td>571945</td>
<td>93.5</td>
<td>92.9</td>
<td>NaN</td>
<td>87.7</td>
<td>82.6</td>
<td>76.0</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
</tr>
<tr>
<th>4</th>
<td>Wainwright, Adam</td>
<td>425794</td>
<td>88.0</td>
<td>88.6</td>
<td>84.3</td>
<td>75.3</td>
<td>82.2</td>
<td>72.8</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
<td>NaN</td>
</tr>
</tbody>
</table>
</div>
<div class="colab-df-buttons">
<div class="colab-df-container">
<button class="colab-df-convert" onclick="convertToInteractive('df-9f24c5f0-d89d-4548-ae95-4d48b44ddd86')" style="display:none;" title="Convert this dataframe to an interactive table.">
<svg height="24px" viewbox="0 -960 960 960" xmlns="http://www.w3.org/2000/svg">
<path d="M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z"></path>
</svg>
</button>
<style>
    .colab-df-container {
      display:flex;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    .colab-df-buttons div {
      margin-bottom: 4px;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>
<script>
      const buttonEl =
        document.querySelector('#df-9f24c5f0-d89d-4548-ae95-4d48b44ddd86 button.colab-df-convert');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      async function convertToInteractive(key) {
        const element = document.querySelector('#df-9f24c5f0-d89d-4548-ae95-4d48b44ddd86');
        const dataTable =
          await google.colab.kernel.invokeFunction('convertToInteractive',
                                                    [key], {});
        if (!dataTable) return;

        const docLinkHtml = 'Like what you see? Visit the ' +
          '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
          + ' to learn more about interactive tables.';
        element.innerHTML = '';
        dataTable['output_type'] = 'display_data';
        await google.colab.output.renderOutput(dataTable, element);
        const docLink = document.createElement('div');
        docLink.innerHTML = docLinkHtml;
        element.appendChild(docLink);
      }
    </script>
</div>
<div id="df-321fc6da-5bb0-4730-90fa-ee6de28d416d">
<button class="colab-df-quickchart" onclick="quickchart('df-321fc6da-5bb0-4730-90fa-ee6de28d416d')" style="display:none;" title="Suggest charts">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<g>
<path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"></path>
</g>
</svg>
</button>
<style>
  .colab-df-quickchart {
      --bg-color: #E8F0FE;
      --fill-color: #1967D2;
      --hover-bg-color: #E2EBFA;
      --hover-fill-color: #174EA6;
      --disabled-fill-color: #AAA;
      --disabled-bg-color: #DDD;
  }

  [theme=dark] .colab-df-quickchart {
      --bg-color: #3B4455;
      --fill-color: #D2E3FC;
      --hover-bg-color: #434B5C;
      --hover-fill-color: #FFFFFF;
      --disabled-bg-color: #3B4455;
      --disabled-fill-color: #666;
  }

  .colab-df-quickchart {
    background-color: var(--bg-color);
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: var(--fill-color);
    height: 32px;
    padding: 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: var(--hover-bg-color);
    box-shadow: 0 1px 2px rgba(60, 64, 67, 0.3), 0 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: var(--button-hover-fill-color);
  }

  .colab-df-quickchart-complete:disabled,
  .colab-df-quickchart-complete:disabled:hover {
    background-color: var(--disabled-bg-color);
    fill: var(--disabled-fill-color);
    box-shadow: none;
  }

  .colab-df-spinner {
    border: 2px solid var(--fill-color);
    border-color: transparent;
    border-bottom-color: var(--fill-color);
    animation:
      spin 1s steps(1) infinite;
  }

  @keyframes spin {
    0% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
      border-left-color: var(--fill-color);
    }
    20% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    30% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
      border-right-color: var(--fill-color);
    }
    40% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    60% {
      border-color: transparent;
      border-right-color: var(--fill-color);
    }
    80% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-bottom-color: var(--fill-color);
    }
    90% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
    }
  }
</style>
<script>
    async function quickchart(key) {
      const quickchartButtonEl =
        document.querySelector('#' + key + ' button');
      quickchartButtonEl.disabled = true;  // To prevent multiple clicks.
      quickchartButtonEl.classList.add('colab-df-spinner');
      try {
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      } catch (error) {
        console.error('Error during call to suggestCharts:', error);
      }
      quickchartButtonEl.classList.remove('colab-df-spinner');
      quickchartButtonEl.classList.add('colab-df-quickchart-complete');
    }
    (() => {
      let quickchartButtonEl =
        document.querySelector('#df-321fc6da-5bb0-4730-90fa-ee6de28d416d button');
      quickchartButtonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';
    })();
  </script>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Description-of-Dataset(s)-and-How-the-Dataset-Can-Be-Used-to-Answer-the-Question:"><strong>Description of Dataset(s) and How the Dataset Can Be Used to Answer the Question:</strong><a class="anchor-link" href="#Description-of-Dataset(s)-and-How-the-Dataset-Can-Be-Used-to-Answer-the-Question:">¶</a></h1><p>The datasets contain detailed baseball performance metrics across 2017-2024, specifically focusing on pitch statistics and batter statistics. The key components of the dataset are:</p>
<p>Pitching Data: This includes yearly statistics on various pitch types, such as fastballs and changeups, across multiple years (2017-2024). For each year, the dataset contains metrics like:
Fastball Average Speed (ff_avg_speed): This represents the average speed of fastballs thrown by pitchers during the season.
Changeup Average Speed (ch_avg_speed): This shows the average speed of changeups thrown by pitchers during the season.</p>
<h1 id="How-the-Dataset-Can-Be-Used-to-Answer-the-Question"><strong>How the Dataset Can Be Used to Answer the Question</strong><a class="anchor-link" href="#How-the-Dataset-Can-Be-Used-to-Answer-the-Question">¶</a></h1><p>The question we aim to answer is how various aspects of pitching and batting performance have changed over time.</p>
<p>Trends in Pitch Speed: The pitching dataset allows us to examine how the median speed of different pitches has evolved over the years. We can analyze whether pitchers are throwing faster or slower pitches over time. This can provide insights into the changing dynamics of pitching strategies or improvements in player training and technology.</p>
<p>By aggregating the data by year and performing statistical analyses, we can generate meaningful insights into how both pitching and batting metrics have changed over time, providing a clearer picture of the trends in baseball performance. This information is valuable for understanding how the game has evolved, how training or technology may have influenced performance, and whether there are any correlations between changes in pitch or exit velocity and overall game outcomes.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Analysis-of-Fastball-pitch-speeds-2017-2024"><strong>Analysis of Fastball pitch speeds 2017-2024</strong><a class="anchor-link" href="#Analysis-of-Fastball-pitch-speeds-2017-2024">¶</a></h1><p>Description of data: The Plot displays the pitch speed change over the years we have available in the data, helping to visualize the data.</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p><a href="https://baseballsavant.mlb.com/leaderboard/pitch-arsenals?year=2017&amp;min=250&amp;type=avg_speed&amp;hand=">Pitch Data</a></p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [123]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1">#Directory containing the CSV files</span>
<span class="n">repo_path</span> <span class="o">=</span> <span class="s1">'/content/drive/MyDrive/Colab Notebooks/MLB-Performance-Measures/MLB-Performance-Measures/'</span>


<span class="n">file_names</span> <span class="o">=</span> <span class="p">[</span><span class="s2">"pitch_arsenals 2017.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2018.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2019.csv"</span><span class="p">,</span>
              <span class="s2">"pitch_arsenals 2020.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2021.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2022.csv"</span><span class="p">,</span>
              <span class="s2">"pitch_arsenals 2023.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2024.csv"</span><span class="p">]</span>

<span class="c1"># Stores median values</span>
<span class="n">median_ff_avg_speed</span> <span class="o">=</span> <span class="p">{}</span>

<span class="c1"># Extracts the median ff_avg_speed from each file</span>
<span class="k">for</span> <span class="n">file_name</span> <span class="ow">in</span> <span class="n">file_names</span><span class="p">:</span>
    <span class="n">file_path</span> <span class="o">=</span> <span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">repo_path</span><span class="p">,</span> <span class="n">file_name</span><span class="p">)</span>

    <span class="k">if</span> <span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">exists</span><span class="p">(</span><span class="n">file_path</span><span class="p">):</span>
        <span class="n">year</span> <span class="o">=</span> <span class="n">file_name</span><span class="o">.</span><span class="n">split</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">'.'</span><span class="p">)[</span><span class="mi">0</span><span class="p">]</span>  <span class="c1"># Gets year from files</span>
        <span class="n">df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">file_path</span><span class="p">)</span>

        <span class="k">if</span> <span class="s1">'ff_avg_speed'</span> <span class="ow">in</span> <span class="n">df</span><span class="o">.</span><span class="n">columns</span><span class="p">:</span>
            <span class="n">median_speed</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">'ff_avg_speed'</span><span class="p">]</span><span class="o">.</span><span class="n">median</span><span class="p">()</span>
            <span class="n">median_ff_avg_speed</span><span class="p">[</span><span class="n">year</span><span class="p">]</span> <span class="o">=</span> <span class="n">median_speed</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s2">"Column 'ff_avg_speed' not found in </span><span class="si">{</span><span class="n">file_name</span><span class="si">}</span><span class="s2">"</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="sa">f</span><span class="s2">"File </span><span class="si">{</span><span class="n">file_name</span><span class="si">}</span><span class="s2"> does not exist in the repository"</span><span class="p">)</span>


<span class="n">median_speed_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="nb">list</span><span class="p">(</span><span class="n">median_ff_avg_speed</span><span class="o">.</span><span class="n">items</span><span class="p">()),</span> <span class="n">columns</span><span class="o">=</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">,</span> <span class="s1">'Median_ff_avg_speed'</span><span class="p">])</span>
<span class="n">median_speed_df</span> <span class="o">=</span> <span class="n">median_speed_df</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">'Year'</span><span class="p">)</span>

<span class="c1"># Plot the results</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">5</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">median_speed_df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">],</span> <span class="n">median_speed_df</span><span class="p">[</span><span class="s1">'Median_ff_avg_speed'</span><span class="p">],</span> <span class="n">marker</span><span class="o">=</span><span class="s1">'o'</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'-'</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'b'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">'Year'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">'Median Fastball Average Speed (mph)'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">'Median Fastball Average Speed from 2017 to 2024'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>

<span class="c1"># Display the DataFrame</span>
<span class="kn">import</span> <span class="nn">IPython.display</span> <span class="k">as</span> <span class="nn">display</span>
<span class="n">display</span><span class="o">.</span><span class="n">display</span><span class="p">(</span><span class="n">median_speed_df</span><span class="p">)</span>
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
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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e1pS4ufnd9vV0P7++2/efvttfv31V6KiolKso2TJkgwaNIiJEycyb948nnzySVq0aEHXrl3tfnm8m1u/VqVLlyZLlix2zyP6/fffGTZsGJs2bUoW5C5fvuzQ693O119/zWOPPcb58+c5f/48AI888ghxcXEsWrTINq2xQ4cOvPnmm0RERFC4cGF+++03zp49S4cOHWznSu37JUnJkiVTPC411530ngsKCrLbnzt37mTvuUOHDvHXX3/d9he+W+u6VZYsWejTpw99+vTh/Pnz/P7773z66aesWLGCjh07sn79ervjb+3b7NmzExgYaOvbQ4cOAdiFgJsl3Rt0+PBhDMPgnXfe4Z133rlt7YULF+b48eO2wHKzpKmW96Nw4cLJVvc8fvw4ZcqUSTatrEKFCrb9NytWrJjddtJ7t2jRoim2p/b7Gcx70lq3bk2lSpX4/PPP7fYlBfWke4hudv369VRNm7ybxYsXc/369fsOsklfs5T6rEKFCqxatYro6OhUrcBntVptK/qtWLEi2Wqovr6+t/2aJO1PSb9+/Vi5ciVfffUVVapUsdv39ttvkzt37hT/wCGSGSlciWQinTt35vnnn+fMmTM0adLktn9tTUxMJH/+/MybNy/F/c7466TVaqVhw4ZcuHCB119/nfLly+Pn50dERAQ9evRIdkO+h4fHfb9mSi5dukRwcDABAQGMHDmS0qVL4+Pjw/bt23n99dft6vjwww/p0aMHP/zwA6tXr6Z///62e6fudDP7ndw84gdw5MgRGjRoQPny5Zk4cSJFixYla9asLF++nEmTJjnlWVSHDh1i69atQPJAAOZ9MjeHq6FDh7Jo0SIGDhzIt99+S44cOXj66adtxzv6fknpF7i0uO7ExEQaNmxoG6G8VdmyZVN9rjx58tCiRQtatGhBvXr1CA8P5/jx48lu+r9bPWDed5XSAgpJIzlJxw0ePDjFET5IHi7TgjMCyO2+b2/XbhhGqs578uRJGjVqRI4cOVi+fDn+/v52+wMDAwFSfP7V6dOnnfIIhnnz5pEjRw63ekbg888/z7Jly5g3b16KIT4wMPC2XxNI+dEUI0aM4JNPPuG9997j2Weftdt36NAhZsyYweTJk/n3339t7devXyc+Pp5jx44REBBgNyIn8qBTuBLJRFq3bs2LL77I5s2b7/gwyNKlS/PLL79Qp06dO/6C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19Qp4s4cDld79uxhx44dlCtXLi3qEREREZF0YBiwe/eNlf02bYKbJyD5+5ujUs2amaNUgYGuq1Uko3A4XNWoUYOTJ08qXImIiIhkMFeuwJo1N6b7RUTY769Y8cboVJ06cMut9SJyFw6Hq379+jFgwACGDBlC5cqVky1o8fDDDzutOBERERG5d4ZhPmsqKUyFh0N8/I39vr7QoMGNB/mWKOGyUkUeCA6Hqw4dOgDQq1cvW5vFYtGCFiIiIiJu4No1+O23G4Hqn3/s95cqZU71a9YMgoPBx8clZYo8kBwOV0ePHk2LOkRERETkHh07diNM/fqrGbCSZM1qhqik6X5lyuhBviJpxeFwVbx48bSoQ0RERERSKS4Ofv/9RqDau9d+f5EiN8JUgwaQPbtr6hTJbFIVrjZv3kzNmjVTdcKYmBiOHj1KxYoV76swEREREbnh33/NJdKXL4ewMHNxiiQeHlC7tjnVr2lTqFRJo1MirpCqcPXss89SqlQpevfuTdOmTfHz80t2zN69e/n666+ZNWsW48ePV7gSERERSYHVCuHhFtatK4yfn4X69VN+ZpTVClu23Bid2rHDfn/+/OYiFE2bQsOGkCtX+tQvIreXqnC1d+9epk+fzttvv03nzp0pW7YshQoVwsfHh4sXL7J//36uXr1K69atWb16NZUrV07rukVEREQynCVLYMAAOHXKE6jBxInmFL4pU6BNG4iMhFWrzDC1ciVcuHDjcy0WePTRG9P9qleHLFlcdikikoJUhSsvLy/69+9P//79+fPPP9mwYQPHjx/n2rVrVKlShVdffZX69euTO3futK5XREREJENasgTatTOXR7/ZqVPQti2ULQuHDtnvz5kTGjc2p/s1bmyOVomI+7qnhwjXqFEjLWoREREReSBZreaI1a3B6mYHD5r/rVLlxuhUzZrg6fBvayLiKvp2FREREUlj69ebI1R38+230L592tcjImlDM3VFRERE0tjp06k7LiEhbesQkbSlcCUiIiKSxlIbmgID07YOEUlbmhYoIiIikoY2bDDvt7oTi8VcNfDJJ9OnJhFJGxq5EhEREUkjCxdCSAhcvAhBQWaIuvXhvknbkyen/LwrEck4UjVy9dFHH6X6hP3797/nYkREREQeBIYBEybAG2+Y261awbx55rOrzOdc3Ti2SBEzWLVp44pKRcSZUhWuJk2a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BYvFtbWJiIjcyuF7rp599lmmT5+erH3GjBl06dLFKUWJiEjmdvYsPP881KhhBitfX3P637590K6dgpWIiLinVI1cDRo0yPaxxWLh888/Z/Xq1dSsWROALVu2cOLECbp165Y2VYqISKYQF2c+q2rECIiKMts6dTLvtSpa1LW1iYiI3E2qwtWOHTvstqtXrw7AkSNHAMibNy958+bl77//dnJ5IiKSWaxYYT7498ABc7taNfO+qieecG1dIiIiqZWqcLV27dq0rkNERDKpgwfNULV8ubmdPz+MHQs9eoCHh0tLExERcYjD91z16tWLK1euJGuPjo6mV69eTilKREQefJcvw+DBULGiGay8vMztgwfhuecUrEREJONxOFzNmTOHa9euJWu/du0aX331lVOKEhGRB5fVCl98AWXLwocfQkICNGsGe/bA++9DjhyurlBEROTepHop9qioKAzDwDAMrly5go+Pj22f1Wpl+fLl5M+fP02KFBGRB8OGDebS6tu3m9vlysGkSdCkiWvrEhERcYZUh6ucOXNisViwWCyULVs22X6LxcKIESOcWpyIyN1YrRAebmHdusL4+VmoX1/TyVzpdv1x8iS8/josWGAeFxAAw4dDnz6QNatLSxYREXGaVE8LXLt2LWvWrMEwDL777jt+/fVX278NGzZw4sQJ3nrrLYcLuHLlCgMHDqR48eL4+vpSu3Zttm7dats/fPhwypcvj5+fH7ly5SIkJIQtW7ak+vzvvfceFouFgQMHOlybiLi3JUugRAlo2NCTiRNr0LChJyVKmO2S/lLqj+LFzaXUy5c3g5XFYj6/6tAhcxELBSsREXmQpHrkKjg4GICjR49SrFgxLE56gmPv3r3Zs2cPc+fOpVChQnz99deEhISwd+9eChcuTNmyZZk6dSqlSpXi2rVrTJo0iUaNGnH48GHy5ct3x3Nv3bqVzz77jIcfftgptYqI+1iyxHyYrGHYt0dEmO3ffQdt2rimtszoTv3xzTfmx088YS6tXq1a+tcnIiKSHlIdrpLs27ePkydP8sT/P3hk2rRpzJw5k4ceeohp06aRK1euVJ/r2rVrLF68mB9++IG6desC5kjVTz/9xPTp0xk9ejSdO3e2+5yJEyfyxRdf8Ndff9GgQYPbnvvq1at06dKFmTNnMnr0aEcvU0TcmNVq3rdz6y/ycKOtVy9zgYQs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kdtx6CHCIpI+EhKgSxdYsgSyZjUDVsOGrq5KRERERO7knlcLFJG0kZAAzz4LixaBlxcsXQqNG7u6KhERERG5G4UrETditUL37vDNN2awWrwYmjZ1dVUiIiIikhoKVyJuwmqFnj1h/nzw9IRvv4XmzV1dlYiIiIiklsKViBtITITnn4e5c8HDwxy5atXK1VWJiIiIiCMUrkRcLDERXnwRZs0yg9WCBdC2raurEhERERFHKVyJuJBhwCuvwOefQ5Ys5shV+/aurkpERERE7oXClYiLGAb07QuffQYWC8yZYz7XSkREREQyJoUrERcwDBg4ED75xAxWs2ZB166urkpERERE7ofClUg6Mwz43//go4/M7c8/N5dfFxEREZGMTeFKJB0ZBrz+OkyaZG7PmAG9erm2JhERERFxDoUrkXRiGPDmm/D+++b29Onm8usiIiIi8mBQuBJJB4YB774L771nbk+dCi+95NqaRERERMS5FK5E0sHIkTB6tPnx5MnQp49LyxERERGRNKBwJZLGRo+G4cPNjz/8EAYMcGk5IiIiIpJGFK5E0tB778E775gfT5gAgwa5th4RERERSTsKVyJp5P33YehQ8+OxY2HIENfWIyIiIiJpS+FKJA1MmgSvvWZ+PHLkjZAlIiIiIg8uhSsRJ/vooxvT/4YNuzEtUEREREQebApXIk40bdqNBSveessMVyIiIiKSOShciTjJZ59B377mx2+8AaNGgcXi2ppEREREJP0oXIk4weef33go8ODB5gIWClYiIiIimYvClch9mjULXnjB/HjgQHPJdQUrERERkczH09UFiGQkViuEh1tYt64wfn4WTp2C554Dw4B+/WDiRAUrERERkcxK4UoklZYsMRerOHXKE6jBxIk39r3yCkyZomAlIiIikpkpXImkwpIl0K6dOUKVkvr1FaxEREREMjvdcyVyF1arOWJ1u2BlsZjPtbJa07cuEREREXEvGrkSuUl0NBw+DIcO3fi3dSucOnX7zzEMOHkS1q+HevXSrVQRERERcTMKV5LpXL8OR47cCE8HD974+N9/7/28p087r0YRERERyXgUruSBFBcH//xjPwKV9O/kydtP8QPInRvKlLnxLyHBfCDw3QQGOq9+EREREcl4FK4kw0pIgGPHUg5Qx45BYuLtPzcgAMqWtQ9RSf9y57Y/1mo1n2UVEZFyKLNY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0ly5QNIdt/379wfHXLlyxdavX29z5861uLg4e+GFF2x4eDjkPEVFRXc8z8DAQHBMIBCw9PR0e/vtt12qbvpxM4/PP//cCgoKLD4+3pKTk+25556znp4elyqdPtzK5MKFC1ZYWGjx8fEWFxdnxcXF1tbW5mKl04cTmezYseOO57j96u6xY8fsiSeesFmzZll2dnbIHPiHm3nczRi4l8m/va+Vl5e7V+w04VYmH3/8seXm5lpcXJwlJiZaQUGB7d69O+Rfr8Dd961bRbq58piZ/csdgwAAAACAu8TjsQAAAADAATRXAAAAAOAAmisAAAAAcADNFQAAAAA4gOYKAAAAABxAcwUAAAAADqC5AgAAAAAH0FwBAAAAgANorgAAAADAATRXAICoZ2Z69tlntWzZsknHdu/eraSkJA0NDUVgZQCAaEJzBQCIeh6PR/v371d7e7v27NkT3D8wMKCtW7dq165dSk9Pd3TOa9euOXo+AMDUR3MFAJgRMjIy9NFHH+nNN9/UwMCAzExr1qxRSUmJCgoKtHz5ciUkJOihhx7SqlWrdPHixeDPNjY2asmSJUpKStK8efNUWlqq/v7+4PHBwUF5PB598cUXKioqUmxsrA4ePBiJMgEAEeQxM4v0IgAAcMvKlSv1xx9/6MUXX9TOnTvV3d2t3NxcVVRU6JVXXtGVK1f01ltv6fr162pubpYkNTQ0yOPxaOHChZqYmND27ds1ODion3/+WTExMRocHNSCBQuUlZWlDz74QAUFBYqNjdXDDz8c4WoBAG6iuQIAzChjY2PKzc3VpUuX1NDQoK6uLrW0tKipqSk4ZmhoSBkZGTp79qxycnImnePixYtKTk5WZ2en8vLygs3Vhx9+qI0bN7pZDgBgCuG2QADAjJKSkqLKyko9/vjjWrlypX755RcdO3ZMCQkJwe2xxx6TpOCtf319ffL5fMrOzlZiYqKysrIkSb/99lvIuRctWuRqLQCAqcUb6QUAAOA2r9crr/efX4ETExNasWKF6urqJo27eVvfihUrlJmZqb179yotLU03btxQXl6erl69GjI+Pj4+/IsHAExZNFcAgBntySefVENDg7KysoIN161+//13nT17Vnv37tXSpUslSa2trW4vEwAwDXBbIABgRquqqtKlS5fk8/l08uRJ9ff3q6mpSatXr1YgENDcuXM1b948ffbZZ/r111/V3NyszZs3R3rZAIApiOYKADCjpaWl6cSJEwoEAiopKVF+fr42bdqkpKQkxcTEKCYmRocPH9apU6eUl5enN954Q++//36klw0AmIJ4WiAAAAAAOIBPrgAAAADAATRXAAAAAOAAmisAAAAAcADNFQAAAAA4gOYKAAAAABxAcwUAAAAADqC5AgAAAAAH0FwBAAAAgANorgAAAADAATRXAAAAAOAAmisAAAAAcMDfnqPi7y29pE4AAAAASUVORK5CYII=
"/>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output" data-mime-type="text/html" tabindex="0">
<div class="colab-df-container" id="df-80ffc41a-d46a-4082-abd2-feae1988b09d">
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
<th>Year</th>
<th>Median_ff_avg_speed</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>2017</td>
<td>93.00</td>
</tr>
<tr>
<th>1</th>
<td>2018</td>
<td>93.05</td>
</tr>
<tr>
<th>2</th>
<td>2019</td>
<td>93.40</td>
</tr>
<tr>
<th>3</th>
<td>2020</td>
<td>93.40</td>
</tr>
<tr>
<th>4</th>
<td>2021</td>
<td>93.60</td>
</tr>
<tr>
<th>5</th>
<td>2022</td>
<td>93.90</td>
</tr>
<tr>
<th>6</th>
<td>2023</td>
<td>94.00</td>
</tr>
<tr>
<th>7</th>
<td>2024</td>
<td>94.20</td>
</tr>
</tbody>
</table>
</div>
<div class="colab-df-buttons">
<div class="colab-df-container">
<button class="colab-df-convert" onclick="convertToInteractive('df-80ffc41a-d46a-4082-abd2-feae1988b09d')" style="display:none;" title="Convert this dataframe to an interactive table.">
<svg height="24px" viewbox="0 -960 960 960" xmlns="http://www.w3.org/2000/svg">
<path d="M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z"></path>
</svg>
</button>
<style>
    .colab-df-container {
      display:flex;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    .colab-df-buttons div {
      margin-bottom: 4px;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>
<script>
      const buttonEl =
        document.querySelector('#df-80ffc41a-d46a-4082-abd2-feae1988b09d button.colab-df-convert');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      async function convertToInteractive(key) {
        const element = document.querySelector('#df-80ffc41a-d46a-4082-abd2-feae1988b09d');
        const dataTable =
          await google.colab.kernel.invokeFunction('convertToInteractive',
                                                    [key], {});
        if (!dataTable) return;

        const docLinkHtml = 'Like what you see? Visit the ' +
          '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
          + ' to learn more about interactive tables.';
        element.innerHTML = '';
        dataTable['output_type'] = 'display_data';
        await google.colab.output.renderOutput(dataTable, element);
        const docLink = document.createElement('div');
        docLink.innerHTML = docLinkHtml;
        element.appendChild(docLink);
      }
    </script>
</div>
<div id="df-64440de9-2b4e-4de7-8646-64a436d50dd5">
<button class="colab-df-quickchart" onclick="quickchart('df-64440de9-2b4e-4de7-8646-64a436d50dd5')" style="display:none;" title="Suggest charts">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<g>
<path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"></path>
</g>
</svg>
</button>
<style>
  .colab-df-quickchart {
      --bg-color: #E8F0FE;
      --fill-color: #1967D2;
      --hover-bg-color: #E2EBFA;
      --hover-fill-color: #174EA6;
      --disabled-fill-color: #AAA;
      --disabled-bg-color: #DDD;
  }

  [theme=dark] .colab-df-quickchart {
      --bg-color: #3B4455;
      --fill-color: #D2E3FC;
      --hover-bg-color: #434B5C;
      --hover-fill-color: #FFFFFF;
      --disabled-bg-color: #3B4455;
      --disabled-fill-color: #666;
  }

  .colab-df-quickchart {
    background-color: var(--bg-color);
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: var(--fill-color);
    height: 32px;
    padding: 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: var(--hover-bg-color);
    box-shadow: 0 1px 2px rgba(60, 64, 67, 0.3), 0 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: var(--button-hover-fill-color);
  }

  .colab-df-quickchart-complete:disabled,
  .colab-df-quickchart-complete:disabled:hover {
    background-color: var(--disabled-bg-color);
    fill: var(--disabled-fill-color);
    box-shadow: none;
  }

  .colab-df-spinner {
    border: 2px solid var(--fill-color);
    border-color: transparent;
    border-bottom-color: var(--fill-color);
    animation:
      spin 1s steps(1) infinite;
  }

  @keyframes spin {
    0% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
      border-left-color: var(--fill-color);
    }
    20% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    30% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
      border-right-color: var(--fill-color);
    }
    40% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    60% {
      border-color: transparent;
      border-right-color: var(--fill-color);
    }
    80% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-bottom-color: var(--fill-color);
    }
    90% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
    }
  }
</style>
<script>
    async function quickchart(key) {
      const quickchartButtonEl =
        document.querySelector('#' + key + ' button');
      quickchartButtonEl.disabled = true;  // To prevent multiple clicks.
      quickchartButtonEl.classList.add('colab-df-spinner');
      try {
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      } catch (error) {
        console.error('Error during call to suggestCharts:', error);
      }
      quickchartButtonEl.classList.remove('colab-df-spinner');
      quickchartButtonEl.classList.add('colab-df-quickchart-complete');
    }
    (() => {
      let quickchartButtonEl =
        document.querySelector('#df-64440de9-2b4e-4de7-8646-64a436d50dd5 button');
      quickchartButtonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';
    })();
  </script>
</div>
<div id="id_cbe68df5-a16c-4c6b-a99f-24f414a28e9f">
<style>
      .colab-df-generate {
        background-color: #E8F0FE;
        border: none;
        border-radius: 50%;
        cursor: pointer;
        display: none;
        fill: #1967D2;
        height: 32px;
        padding: 0 0 0 0;
        width: 32px;
      }

      .colab-df-generate:hover {
        background-color: #E2EBFA;
        box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
        fill: #174EA6;
      }

      [theme=dark] .colab-df-generate {
        background-color: #3B4455;
        fill: #D2E3FC;
      }

      [theme=dark] .colab-df-generate:hover {
        background-color: #434B5C;
        box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
        filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
        fill: #FFFFFF;
      }
    </style>
<button class="colab-df-generate" onclick="generateWithVariable('median_speed_df')" style="display:none;" title="Generate code using this dataframe.">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<path d="M7,19H8.4L18.45,9,17,7.55,7,17.6ZM5,21V16.75L18.45,3.32a2,2,0,0,1,2.83,0l1.4,1.43a1.91,1.91,0,0,1,.58,1.4,1.91,1.91,0,0,1-.58,1.4L9.25,21ZM18.45,9,17,7.55Zm-12,3A5.31,5.31,0,0,0,4.9,8.1,5.31,5.31,0,0,0,1,6.5,5.31,5.31,0,0,0,4.9,4.9,5.31,5.31,0,0,0,6.5,1,5.31,5.31,0,0,0,8.1,4.9,5.31,5.31,0,0,0,12,6.5,5.46,5.46,0,0,0,6.5,12Z"></path>
</svg>
</button>
<script>
      (() => {
      const buttonEl =
        document.querySelector('#id_cbe68df5-a16c-4c6b-a99f-24f414a28e9f button.colab-df-generate');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      buttonEl.onclick = () => {
        google.colab.notebook.generateWithVariable('median_speed_df');
      }
      })();
    </script>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Analysis-of-Curveball-pitch-speeds-2017-2024"><strong>Analysis of Curveball pitch speeds 2017-2024</strong><a class="anchor-link" href="#Analysis-of-Curveball-pitch-speeds-2017-2024">¶</a></h1><p>Description of data: providing variation in the data we are analyzing and including more pitchers than may focus more so on the fastball or changeup. The Plot displays the pitch speed change over the years we have available in the data.
<a href="https://baseballsavant.mlb.com/leaderboard/pitch-arsenals?year=2017&amp;min=250&amp;type=avg_speed&amp;hand=">Pitch Data</a></p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [116]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">repo_path</span> <span class="o">=</span> <span class="s1">'/content/drive/MyDrive/Colab Notebooks/MLB-Performance-Measures/MLB-Performance-Measures/'</span>

<span class="c1"># List of file paths</span>
<span class="n">file_paths</span> <span class="o">=</span> <span class="p">[</span>
    <span class="s2">"pitch_arsenals 2017.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2018.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2019.csv"</span><span class="p">,</span>
    <span class="s2">"pitch_arsenals 2020.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2021.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2022.csv"</span><span class="p">,</span>
    <span class="s2">"pitch_arsenals 2023.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2024.csv"</span>
<span class="p">]</span>


<span class="n">stats_dict</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s1">'Year'</span><span class="p">:</span> <span class="p">[],</span>
    <span class="s1">'Median_CU_Speed'</span><span class="p">:</span> <span class="p">[],</span> <span class="s1">'Std_CU_Speed'</span><span class="p">:</span> <span class="p">[],</span> <span class="s1">'IQR_CU_Speed'</span><span class="p">:</span> <span class="p">[]</span>
<span class="p">}</span>

<span class="c1"># Loop through each file</span>
<span class="k">for</span> <span class="n">file_path</span> <span class="ow">in</span> <span class="n">file_paths</span><span class="p">:</span>
    <span class="n">full_path</span> <span class="o">=</span> <span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">repo_path</span><span class="p">,</span> <span class="n">file_path</span><span class="p">)</span>
    <span class="n">year</span> <span class="o">=</span> <span class="n">file_path</span><span class="o">.</span><span class="n">split</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">'.'</span><span class="p">)[</span><span class="mi">0</span><span class="p">]</span>
    <span class="n">df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">full_path</span><span class="p">)</span>

    <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">year</span><span class="p">)</span>

    <span class="k">for</span> <span class="n">pitch_type</span> <span class="ow">in</span> <span class="p">[</span><span class="s1">'cu_avg_speed'</span><span class="p">]:</span>
        <span class="k">if</span> <span class="n">pitch_type</span> <span class="ow">in</span> <span class="n">df</span><span class="o">.</span><span class="n">columns</span><span class="p">:</span>
            <span class="n">median</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">median</span><span class="p">()</span>
            <span class="n">std_dev</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">std</span><span class="p">()</span>
            <span class="n">iqr</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">quantile</span><span class="p">(</span><span class="mf">0.75</span><span class="p">)</span> <span class="o">-</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">quantile</span><span class="p">(</span><span class="mf">0.25</span><span class="p">)</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="n">median</span><span class="p">,</span> <span class="n">std_dev</span><span class="p">,</span> <span class="n">iqr</span> <span class="o">=</span> <span class="kc">None</span><span class="p">,</span> <span class="kc">None</span><span class="p">,</span> <span class="kc">None</span>  <span class="c1"># missing columns</span>

        <span class="c1"># Store values in the dictionary</span>
        <span class="k">if</span> <span class="n">pitch_type</span> <span class="o">==</span> <span class="s1">'cu_avg_speed'</span><span class="p">:</span>
            <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'Median_CU_Speed'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">median</span><span class="p">)</span>
            <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'Std_CU_Speed'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">std_dev</span><span class="p">)</span>
            <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'IQR_CU_Speed'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">iqr</span><span class="p">)</span>


<span class="n">summary_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">stats_dict</span><span class="p">)</span>
<span class="n">summary_df</span> <span class="o">=</span> <span class="n">summary_df</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">'Year'</span><span class="p">)</span>

<span class="c1"># Plot the results</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">5</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">summary_df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">],</span> <span class="n">summary_df</span><span class="p">[</span><span class="s1">'Median_CU_Speed'</span><span class="p">],</span> <span class="n">marker</span><span class="o">=</span><span class="s1">'o'</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'-'</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'b'</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">'Median CU Speed'</span><span class="p">)</span>


<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">'Year'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">'Median Curveball Speed (mph)'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">'Median Curveball Speed from 2017 to 2024'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">()</span>


<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'--'</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.6</span><span class="p">)</span>

<span class="c1"># plot</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>


<span class="kn">import</span> <span class="nn">IPython.display</span> <span class="k">as</span> <span class="nn">display</span>
<span class="n">display</span><span class="o">.</span><span class="n">display</span><span class="p">(</span><span class="n">summary_df</span><span class="p">)</span>
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
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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0bRe2WmVhxDC+ry5/fbbxejRo0VmZqY4fPiwZrUahVaZrFu3Tri6uoqVK1faHFNSUqJpvUagVSYrVqwQ27ZtE0ePHhVHjx4Va9asEd7e3mLevHma1is7Lf/dupLe0wLZXGkAQL0fKSkp1mMuXboknnjiCdGmTRvh6ekphg4dKs6cOWNznp49e9Z7nhMnTliPsVgsIiQkRMydO1ej6oxHyzzef/990bVrV+Hl5SUCAgLEX//6V3HkyBGNKjUOrTI5f/68uPPOO4WXl5fw9PQUffr0EQcPHtSwUuOwRybz58+v9xy1f7v7xRdfiC5dugh3d3cRGRlp8xik0jKPphxD2mXS0L9rEyZM0K5Yg9Aqk1dffVV06tRJeHp6Ch8fH9G1a1fx+uuv27z1Cmn779aV9G6uTEII0cArBomIiIiIiKiJOB6LiIiIiIjIDthcERERERER2QGbKyIiIiIiIjtgc0VERERERGQHbK6IiIiIiIjsgM0VERERERGRHbC5IiIiIiIisgM2V0RERERERHbA5oqIiIiIiMgO2FwREZHTE0Kgb9++6N+/f53vvf766/D19UVhYaEOOyMiImfC5oqIiJyeyWRCSkoKvv76a7z55pvW9RMnTmD27Nl47bXXEBISYtfHvHz5sl3PR0RE8mNzRUREzUJoaCiWL1+Op59+GidOnIAQAo888gji4+PRtWtX/OUvf0GrVq3Qtm1bjBs3DhcuXLD+2U8++QR//vOf4evrC39/fwwcOBB5eXnW7+fn58NkMmHDhg3o2bMnPDw8sG7dOj3KJCIiHZmEEELvTRAREWllyJAhKC0tRUJCAl544QUcPnwYnTp1wqRJkzB+/HhcunQJzzzzDH777Tfs2rULALB582aYTCZ07twZFRUVeO6555Cfn4+srCy4uLggPz8f7dq1Q0REBJYsWYKuXbvCw8MDN998s87VEhGRlthcERFRs3Lu3Dl06tQJxcXF2Lx5M3JycrBv3z7s3LnTekxhYSFCQ0ORm5uL6OjoOue4cOECAgICkJ2djdjYWGtztWzZMkybNk3LcoiISCJ8WSARETUrgYGBmDx5Mm699VYMGTIE3333Hb744gu0atXK+hETEwMA1pf+HTt2DKNGjUJkZCR8fHwQEREBADh16pTNubt3765pLUREJBdXvTdARESkNVdXV7i6qv8XWFFRgUGDBuHFF1+sc1zNy/oGDRqE8PBwrF69GsHBwVAUBbGxsaiurrY53svLy/GbJyIiabG5IiKiZq1bt27YvHkzIiIirA3XlS5evIjc3FysXr0a9957LwBg//79Wm+TiIgMgC8LJCKiZi0xMRHFxcUYNWoUDh06hLy8POzcuRMPP/wwLBYL2rRpA39/f7z11lv48ccfsWvXLsycOVPvbRMRkYTYXBERUbMWHByML7/8EhaLBfHx8YiLi8P06dPh6+sLFxcXuLi4YP369cjIyEBsbCxmzJiBl19+We9tExGRhDgtkIiIiIiIyA545YqIiIiIiMgO2FwRERERERHZAZsrIiIiIiIiO2BzRUREREREZAdsroiIiIiIiOyAzRUREREREZEdsLkiIiIiIiKyAzZXREREREREdsDmioiIiIiIyA7YXBEREREREdkBmysiIiIiIiI7+H/rGS4p2nreQQAAAABJRU5ErkJggg==
"/>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output" data-mime-type="text/html" tabindex="0">
<div class="colab-df-container" id="df-6639d277-fad2-4e73-b885-1ed85916c016">
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
<th>Year</th>
<th>Median_CU_Speed</th>
<th>Std_CU_Speed</th>
<th>IQR_CU_Speed</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>2017</td>
<td>78.20</td>
<td>3.551599</td>
<td>4.750</td>
</tr>
<tr>
<th>1</th>
<td>2018</td>
<td>78.40</td>
<td>3.563401</td>
<td>4.975</td>
</tr>
<tr>
<th>2</th>
<td>2019</td>
<td>79.10</td>
<td>3.226963</td>
<td>4.400</td>
</tr>
<tr>
<th>3</th>
<td>2020</td>
<td>78.70</td>
<td>3.470827</td>
<td>4.400</td>
</tr>
<tr>
<th>4</th>
<td>2021</td>
<td>78.80</td>
<td>3.525986</td>
<td>4.525</td>
</tr>
<tr>
<th>5</th>
<td>2022</td>
<td>79.30</td>
<td>3.388217</td>
<td>4.300</td>
</tr>
<tr>
<th>6</th>
<td>2023</td>
<td>79.50</td>
<td>3.484324</td>
<td>4.725</td>
</tr>
<tr>
<th>7</th>
<td>2024</td>
<td>79.65</td>
<td>3.425497</td>
<td>4.300</td>
</tr>
</tbody>
</table>
</div>
<div class="colab-df-buttons">
<div class="colab-df-container">
<button class="colab-df-convert" onclick="convertToInteractive('df-6639d277-fad2-4e73-b885-1ed85916c016')" style="display:none;" title="Convert this dataframe to an interactive table.">
<svg height="24px" viewbox="0 -960 960 960" xmlns="http://www.w3.org/2000/svg">
<path d="M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z"></path>
</svg>
</button>
<style>
    .colab-df-container {
      display:flex;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    .colab-df-buttons div {
      margin-bottom: 4px;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>
<script>
      const buttonEl =
        document.querySelector('#df-6639d277-fad2-4e73-b885-1ed85916c016 button.colab-df-convert');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      async function convertToInteractive(key) {
        const element = document.querySelector('#df-6639d277-fad2-4e73-b885-1ed85916c016');
        const dataTable =
          await google.colab.kernel.invokeFunction('convertToInteractive',
                                                    [key], {});
        if (!dataTable) return;

        const docLinkHtml = 'Like what you see? Visit the ' +
          '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
          + ' to learn more about interactive tables.';
        element.innerHTML = '';
        dataTable['output_type'] = 'display_data';
        await google.colab.output.renderOutput(dataTable, element);
        const docLink = document.createElement('div');
        docLink.innerHTML = docLinkHtml;
        element.appendChild(docLink);
      }
    </script>
</div>
<div id="df-e4512477-4a03-40bf-8027-9b99695c8b60">
<button class="colab-df-quickchart" onclick="quickchart('df-e4512477-4a03-40bf-8027-9b99695c8b60')" style="display:none;" title="Suggest charts">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<g>
<path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"></path>
</g>
</svg>
</button>
<style>
  .colab-df-quickchart {
      --bg-color: #E8F0FE;
      --fill-color: #1967D2;
      --hover-bg-color: #E2EBFA;
      --hover-fill-color: #174EA6;
      --disabled-fill-color: #AAA;
      --disabled-bg-color: #DDD;
  }

  [theme=dark] .colab-df-quickchart {
      --bg-color: #3B4455;
      --fill-color: #D2E3FC;
      --hover-bg-color: #434B5C;
      --hover-fill-color: #FFFFFF;
      --disabled-bg-color: #3B4455;
      --disabled-fill-color: #666;
  }

  .colab-df-quickchart {
    background-color: var(--bg-color);
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: var(--fill-color);
    height: 32px;
    padding: 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: var(--hover-bg-color);
    box-shadow: 0 1px 2px rgba(60, 64, 67, 0.3), 0 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: var(--button-hover-fill-color);
  }

  .colab-df-quickchart-complete:disabled,
  .colab-df-quickchart-complete:disabled:hover {
    background-color: var(--disabled-bg-color);
    fill: var(--disabled-fill-color);
    box-shadow: none;
  }

  .colab-df-spinner {
    border: 2px solid var(--fill-color);
    border-color: transparent;
    border-bottom-color: var(--fill-color);
    animation:
      spin 1s steps(1) infinite;
  }

  @keyframes spin {
    0% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
      border-left-color: var(--fill-color);
    }
    20% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    30% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
      border-right-color: var(--fill-color);
    }
    40% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    60% {
      border-color: transparent;
      border-right-color: var(--fill-color);
    }
    80% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-bottom-color: var(--fill-color);
    }
    90% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
    }
  }
</style>
<script>
    async function quickchart(key) {
      const quickchartButtonEl =
        document.querySelector('#' + key + ' button');
      quickchartButtonEl.disabled = true;  // To prevent multiple clicks.
      quickchartButtonEl.classList.add('colab-df-spinner');
      try {
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      } catch (error) {
        console.error('Error during call to suggestCharts:', error);
      }
      quickchartButtonEl.classList.remove('colab-df-spinner');
      quickchartButtonEl.classList.add('colab-df-quickchart-complete');
    }
    (() => {
      let quickchartButtonEl =
        document.querySelector('#df-e4512477-4a03-40bf-8027-9b99695c8b60 button');
      quickchartButtonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';
    })();
  </script>
</div>
<div id="id_dbf94e16-8075-4b3e-b633-98d4c60a07d3">
<style>
      .colab-df-generate {
        background-color: #E8F0FE;
        border: none;
        border-radius: 50%;
        cursor: pointer;
        display: none;
        fill: #1967D2;
        height: 32px;
        padding: 0 0 0 0;
        width: 32px;
      }

      .colab-df-generate:hover {
        background-color: #E2EBFA;
        box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
        fill: #174EA6;
      }

      [theme=dark] .colab-df-generate {
        background-color: #3B4455;
        fill: #D2E3FC;
      }

      [theme=dark] .colab-df-generate:hover {
        background-color: #434B5C;
        box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
        filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
        fill: #FFFFFF;
      }
    </style>
<button class="colab-df-generate" onclick="generateWithVariable('summary_df')" style="display:none;" title="Generate code using this dataframe.">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<path d="M7,19H8.4L18.45,9,17,7.55,7,17.6ZM5,21V16.75L18.45,3.32a2,2,0,0,1,2.83,0l1.4,1.43a1.91,1.91,0,0,1,.58,1.4,1.91,1.91,0,0,1-.58,1.4L9.25,21ZM18.45,9,17,7.55Zm-12,3A5.31,5.31,0,0,0,4.9,8.1,5.31,5.31,0,0,0,1,6.5,5.31,5.31,0,0,0,4.9,4.9,5.31,5.31,0,0,0,6.5,1,5.31,5.31,0,0,0,8.1,4.9,5.31,5.31,0,0,0,12,6.5,5.46,5.46,0,0,0,6.5,12Z"></path>
</svg>
</button>
<script>
      (() => {
      const buttonEl =
        document.querySelector('#id_dbf94e16-8075-4b3e-b633-98d4c60a07d3 button.colab-df-generate');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      buttonEl.onclick = () => {
        google.colab.notebook.generateWithVariable('summary_df');
      }
      })();
    </script>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span> 
</pre></div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Analysis-of-Changeup-pitch-speeds-2017-2024"><strong>Analysis of Changeup pitch speeds 2017-2024</strong><a class="anchor-link" href="#Analysis-of-Changeup-pitch-speeds-2017-2024">¶</a></h1><p>Description of data: The Changeup is another highly thrown pitch, providing variation in the data we are analyzing and including more pitchers than may focus more so on the curveball. The Plot displays the pitch speed change over the years we have available in the data, helping to visualize the data.
<a href="https://baseballsavant.mlb.com/leaderboard/pitch-arsenals?year=2017&amp;min=250&amp;type=avg_speed&amp;hand=">Pitch Data</a></p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [117]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">repo_path</span> <span class="o">=</span> <span class="s1">'/content/drive/MyDrive/Colab Notebooks/MLB-Performance-Measures/MLB-Performance-Measures/'</span>

<span class="c1"># File paths</span>
<span class="n">file_paths</span> <span class="o">=</span> <span class="p">[</span>
    <span class="s2">"pitch_arsenals 2017.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2018.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2019.csv"</span><span class="p">,</span>
    <span class="s2">"pitch_arsenals 2020.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2021.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2022.csv"</span><span class="p">,</span>
    <span class="s2">"pitch_arsenals 2023.csv"</span><span class="p">,</span> <span class="s2">"pitch_arsenals 2024.csv"</span>
<span class="p">]</span>

<span class="c1"># Dictionary to store statistics for each pitch type</span>
<span class="n">stats_dict</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s1">'Year'</span><span class="p">:</span> <span class="p">[],</span>
    <span class="s1">'Median_CH_Speed'</span><span class="p">:</span> <span class="p">[],</span> <span class="s1">'Std_CH_Speed'</span><span class="p">:</span> <span class="p">[],</span> <span class="s1">'IQR_CH_Speed'</span><span class="p">:</span> <span class="p">[]</span>
<span class="p">}</span>


<span class="k">for</span> <span class="n">file_path</span> <span class="ow">in</span> <span class="n">file_paths</span><span class="p">:</span>
    <span class="n">full_path</span> <span class="o">=</span> <span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">repo_path</span><span class="p">,</span> <span class="n">file_path</span><span class="p">)</span>  <span class="c1"># Create the full file path</span>
    <span class="n">year</span> <span class="o">=</span> <span class="n">file_path</span><span class="o">.</span><span class="n">split</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span><span class="o">.</span><span class="n">split</span><span class="p">(</span><span class="s1">'.'</span><span class="p">)[</span><span class="mi">0</span><span class="p">]</span>  <span class="c1"># Extract year from filename</span>
    <span class="n">df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">full_path</span><span class="p">)</span>

    <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">year</span><span class="p">)</span>

    <span class="k">for</span> <span class="n">pitch_type</span> <span class="ow">in</span> <span class="p">[</span><span class="s1">'ch_avg_speed'</span><span class="p">]:</span>
        <span class="k">if</span> <span class="n">pitch_type</span> <span class="ow">in</span> <span class="n">df</span><span class="o">.</span><span class="n">columns</span><span class="p">:</span>
            <span class="n">median</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">median</span><span class="p">()</span>
            <span class="n">std_dev</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">std</span><span class="p">()</span>
            <span class="n">iqr</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">quantile</span><span class="p">(</span><span class="mf">0.75</span><span class="p">)</span> <span class="o">-</span> <span class="n">df</span><span class="p">[</span><span class="n">pitch_type</span><span class="p">]</span><span class="o">.</span><span class="n">quantile</span><span class="p">(</span><span class="mf">0.25</span><span class="p">)</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="n">median</span><span class="p">,</span> <span class="n">std_dev</span><span class="p">,</span> <span class="n">iqr</span> <span class="o">=</span> <span class="kc">None</span><span class="p">,</span> <span class="kc">None</span><span class="p">,</span> <span class="kc">None</span>  <span class="c1"># Missing columns</span>


        <span class="k">if</span> <span class="n">pitch_type</span> <span class="o">==</span> <span class="s1">'ch_avg_speed'</span><span class="p">:</span>
            <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'Median_CH_Speed'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">median</span><span class="p">)</span>
            <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'Std_CH_Speed'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">std_dev</span><span class="p">)</span>
            <span class="n">stats_dict</span><span class="p">[</span><span class="s1">'IQR_CH_Speed'</span><span class="p">]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">iqr</span><span class="p">)</span>


<span class="n">summary_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">stats_dict</span><span class="p">)</span>
<span class="n">summary_df</span> <span class="o">=</span> <span class="n">summary_df</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">'Year'</span><span class="p">)</span>

<span class="c1"># Plot the results</span>
<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="mi">5</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">summary_df</span><span class="p">[</span><span class="s1">'Year'</span><span class="p">],</span> <span class="n">summary_df</span><span class="p">[</span><span class="s1">'Median_CH_Speed'</span><span class="p">],</span> <span class="n">marker</span><span class="o">=</span><span class="s1">'o'</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'-'</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'b'</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s1">'Median CH Speed'</span><span class="p">)</span>


<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">'Year'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">'Median Changeup Speed (mph)'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">'Median Changeup Speed from 2017 to 2024'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">()</span>


<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">,</span> <span class="n">linestyle</span><span class="o">=</span><span class="s1">'--'</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.6</span><span class="p">)</span>

<span class="c1"># Show the plot</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>


<span class="kn">import</span> <span class="nn">IPython.display</span> <span class="k">as</span> <span class="nn">display</span>
<span class="n">display</span><span class="o">.</span><span class="n">display</span><span class="p">(</span><span class="n">summary_df</span><span class="p">)</span>
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
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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
"/>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output" data-mime-type="text/html" tabindex="0">
<div class="colab-df-container" id="df-1d5b9f6f-084d-4a5c-940a-290215ca882c">
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
<th>Year</th>
<th>Median_CH_Speed</th>
<th>Std_CH_Speed</th>
<th>IQR_CH_Speed</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>2017</td>
<td>85.15</td>
<td>3.231576</td>
<td>4.100</td>
</tr>
<tr>
<th>1</th>
<td>2018</td>
<td>85.40</td>
<td>3.348806</td>
<td>4.100</td>
</tr>
<tr>
<th>2</th>
<td>2019</td>
<td>85.60</td>
<td>3.276589</td>
<td>3.800</td>
</tr>
<tr>
<th>3</th>
<td>2020</td>
<td>85.90</td>
<td>3.183195</td>
<td>4.100</td>
</tr>
<tr>
<th>4</th>
<td>2021</td>
<td>86.00</td>
<td>3.179181</td>
<td>3.725</td>
</tr>
<tr>
<th>5</th>
<td>2022</td>
<td>86.20</td>
<td>2.966423</td>
<td>3.800</td>
</tr>
<tr>
<th>6</th>
<td>2023</td>
<td>86.20</td>
<td>3.022285</td>
<td>4.200</td>
</tr>
<tr>
<th>7</th>
<td>2024</td>
<td>86.30</td>
<td>3.177698</td>
<td>4.200</td>
</tr>
</tbody>
</table>
</div>
<div class="colab-df-buttons">
<div class="colab-df-container">
<button class="colab-df-convert" onclick="convertToInteractive('df-1d5b9f6f-084d-4a5c-940a-290215ca882c')" style="display:none;" title="Convert this dataframe to an interactive table.">
<svg height="24px" viewbox="0 -960 960 960" xmlns="http://www.w3.org/2000/svg">
<path d="M120-120v-720h720v720H120Zm60-500h600v-160H180v160Zm220 220h160v-160H400v160Zm0 220h160v-160H400v160ZM180-400h160v-160H180v160Zm440 0h160v-160H620v160ZM180-180h160v-160H180v160Zm440 0h160v-160H620v160Z"></path>
</svg>
</button>
<style>
    .colab-df-container {
      display:flex;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    .colab-df-buttons div {
      margin-bottom: 4px;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>
<script>
      const buttonEl =
        document.querySelector('#df-1d5b9f6f-084d-4a5c-940a-290215ca882c button.colab-df-convert');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      async function convertToInteractive(key) {
        const element = document.querySelector('#df-1d5b9f6f-084d-4a5c-940a-290215ca882c');
        const dataTable =
          await google.colab.kernel.invokeFunction('convertToInteractive',
                                                    [key], {});
        if (!dataTable) return;

        const docLinkHtml = 'Like what you see? Visit the ' +
          '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
          + ' to learn more about interactive tables.';
        element.innerHTML = '';
        dataTable['output_type'] = 'display_data';
        await google.colab.output.renderOutput(dataTable, element);
        const docLink = document.createElement('div');
        docLink.innerHTML = docLinkHtml;
        element.appendChild(docLink);
      }
    </script>
</div>
<div id="df-dbb20696-0689-4bc9-95eb-8d5c6e26aec7">
<button class="colab-df-quickchart" onclick="quickchart('df-dbb20696-0689-4bc9-95eb-8d5c6e26aec7')" style="display:none;" title="Suggest charts">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<g>
<path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"></path>
</g>
</svg>
</button>
<style>
  .colab-df-quickchart {
      --bg-color: #E8F0FE;
      --fill-color: #1967D2;
      --hover-bg-color: #E2EBFA;
      --hover-fill-color: #174EA6;
      --disabled-fill-color: #AAA;
      --disabled-bg-color: #DDD;
  }

  [theme=dark] .colab-df-quickchart {
      --bg-color: #3B4455;
      --fill-color: #D2E3FC;
      --hover-bg-color: #434B5C;
      --hover-fill-color: #FFFFFF;
      --disabled-bg-color: #3B4455;
      --disabled-fill-color: #666;
  }

  .colab-df-quickchart {
    background-color: var(--bg-color);
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: var(--fill-color);
    height: 32px;
    padding: 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: var(--hover-bg-color);
    box-shadow: 0 1px 2px rgba(60, 64, 67, 0.3), 0 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: var(--button-hover-fill-color);
  }

  .colab-df-quickchart-complete:disabled,
  .colab-df-quickchart-complete:disabled:hover {
    background-color: var(--disabled-bg-color);
    fill: var(--disabled-fill-color);
    box-shadow: none;
  }

  .colab-df-spinner {
    border: 2px solid var(--fill-color);
    border-color: transparent;
    border-bottom-color: var(--fill-color);
    animation:
      spin 1s steps(1) infinite;
  }

  @keyframes spin {
    0% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
      border-left-color: var(--fill-color);
    }
    20% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    30% {
      border-color: transparent;
      border-left-color: var(--fill-color);
      border-top-color: var(--fill-color);
      border-right-color: var(--fill-color);
    }
    40% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-top-color: var(--fill-color);
    }
    60% {
      border-color: transparent;
      border-right-color: var(--fill-color);
    }
    80% {
      border-color: transparent;
      border-right-color: var(--fill-color);
      border-bottom-color: var(--fill-color);
    }
    90% {
      border-color: transparent;
      border-bottom-color: var(--fill-color);
    }
  }
</style>
<script>
    async function quickchart(key) {
      const quickchartButtonEl =
        document.querySelector('#' + key + ' button');
      quickchartButtonEl.disabled = true;  // To prevent multiple clicks.
      quickchartButtonEl.classList.add('colab-df-spinner');
      try {
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      } catch (error) {
        console.error('Error during call to suggestCharts:', error);
      }
      quickchartButtonEl.classList.remove('colab-df-spinner');
      quickchartButtonEl.classList.add('colab-df-quickchart-complete');
    }
    (() => {
      let quickchartButtonEl =
        document.querySelector('#df-dbb20696-0689-4bc9-95eb-8d5c6e26aec7 button');
      quickchartButtonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';
    })();
  </script>
</div>
<div id="id_26060746-7218-466a-a4bc-49da27db2ae4">
<style>
      .colab-df-generate {
        background-color: #E8F0FE;
        border: none;
        border-radius: 50%;
        cursor: pointer;
        display: none;
        fill: #1967D2;
        height: 32px;
        padding: 0 0 0 0;
        width: 32px;
      }

      .colab-df-generate:hover {
        background-color: #E2EBFA;
        box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
        fill: #174EA6;
      }

      [theme=dark] .colab-df-generate {
        background-color: #3B4455;
        fill: #D2E3FC;
      }

      [theme=dark] .colab-df-generate:hover {
        background-color: #434B5C;
        box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
        filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
        fill: #FFFFFF;
      }
    </style>
<button class="colab-df-generate" onclick="generateWithVariable('summary_df')" style="display:none;" title="Generate code using this dataframe.">
<svg height="24px" viewbox="0 0 24 24" width="24px" xmlns="http://www.w3.org/2000/svg">
<path d="M7,19H8.4L18.45,9,17,7.55,7,17.6ZM5,21V16.75L18.45,3.32a2,2,0,0,1,2.83,0l1.4,1.43a1.91,1.91,0,0,1,.58,1.4,1.91,1.91,0,0,1-.58,1.4L9.25,21ZM18.45,9,17,7.55Zm-12,3A5.31,5.31,0,0,0,4.9,8.1,5.31,5.31,0,0,0,1,6.5,5.31,5.31,0,0,0,4.9,4.9,5.31,5.31,0,0,0,6.5,1,5.31,5.31,0,0,0,8.1,4.9,5.31,5.31,0,0,0,12,6.5,5.46,5.46,0,0,0,6.5,12Z"></path>
</svg>
</button>
<script>
      (() => {
      const buttonEl =
        document.querySelector('#id_26060746-7218-466a-a4bc-49da27db2ae4 button.colab-df-generate');
      buttonEl.style.display =
        google.colab.kernel.accessAllowed ? 'block' : 'none';

      buttonEl.onclick = () => {
        google.colab.notebook.generateWithVariable('summary_df');
      }
      })();
    </script>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Batter-Data:"><strong>Batter Data:</strong><a class="anchor-link" href="#Batter-Data:">¶</a></h1>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Analysis-of-Exit-Velocity-speeds-2017-2024"><strong>Analysis of Exit Velocity speeds 2017-2024</strong><a class="anchor-link" href="#Analysis-of-Exit-Velocity-speeds-2017-2024">¶</a></h1><p><a href="https://baseballsavant.mlb.com/leaderboard/custom?year=2024%2C2023%2C2022%2C2021%2C2020%2C2019%2C2018%2C2017&amp;type=batter&amp;filter=&amp;min=q&amp;selections=player_age%2Cab%2Cpa%2Chit%2Csingle%2Cdouble%2Ctriple%2Chome_run%2Cstrikeout%2Cwalk%2Ck_percent%2Cbb_percent%2Cbatting_avg%2Cslg_percent%2Con_base_percent%2Con_base_plus_slg%2Cwoba%2Cxwoba%2Cavg_swing_speed%2Cexit_velocity_avg%2Csweet_spot_percent%2Cbarrel_batted_rate%2Chard_hit_percent%2Cavg_best_speed%2Cavg_hyper_speed%2Cwhiff_percent%2Cswing_percent&amp;chart=false&amp;x=player_age&amp;y=player_age&amp;r=no&amp;chartType=beeswarm&amp;sort=xwoba&amp;sortDir=asc">Batter  Data</a></p>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [117]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span>
</pre></div>
</div>
</div>
</div>
</div>
</div>
</main>
</body>
</html>
