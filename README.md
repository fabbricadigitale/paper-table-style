Paper-table-style
=================
A shared style component to make responsive your HTML table extended with Polymer 2.0 and Material Design

Examples:
Import `paper-table-style.html` and include **paper-table-style** in the style of an element's definition.

```html
<dom-module id="app-table">
    <template>
        <style include="paper-table-style">
        </style>
    </template>
    <table>
        <thead>
            <tr>
                <th>Header1</th>
                <th>Header2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Value11</td>
                <td>Value12</td>
            </tr>
            <tr>
                <td>Value21</td>
                <td>Value22</td>
            </tr>
        </tbody>
    </table>
</dom-module>
```

### Styling
Custom property                             | Description                                                | Default
--------------------------------------------|------------------------------------------------------------|------------------
`--paper-table-style-row-height`            | The row height.                                            | 48px
`--paper-table-style-divider-color`         | The divider color.                                         | --divider-color
`--paper-table-style-height`                | The height not scrollable of the table.                    | 150px
`--paper-table-style-scrollbar-width`       | The width of the scrollbar.                                | 8px
`--paper-table-style-scrollbar-color`       | The colour of the scrollbar.                               | --divider-color

Mixin                                       | Description
--------------------------------------------|--------------------------------------------------------------------------
`--paper-table-style`                       | ...
`--paper-table-style-th`                    | ...
`--paper-table-style-td`                    | ...


