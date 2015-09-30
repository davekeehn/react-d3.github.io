Scatter Plot Component:

```js


import {
  default as React,
  Component,
} from 'react';

import {
  ScatterTooltip as ScatterTooltip
} from 'react-d3-tooltip';


// Your Setting props!

const chartSeries = [
      {
        field: 'close',
        name: 'Price',
        color: '#ff7f0e',
        area: true
      }
    ]

// or multi

const chartSeries = [
      {
        field: 'New York',
        name: 'New York Temp',
        color: '#ff7f0e',
        symbol: "cross"
      },
      {
        field: 'San Francisco',
        name: 'San Francisco Temp',
        color: '#2ca02c',
        symbol: 'diamond'
      },
      {
        field: 'Austin',
        name: 'Austin Temp',
        color: '#7777ff',
        symbol: 'triangle-down'
      }
    ]

// Your other setting props

(() => {

  React.render(
    <ScatterTooltip {pass all your props and chartSeries here!} />,
    document.getElementById('data_container')
  )
})()


// And you have a beautiful chart in react!
```

<a href="/tooltip/scatter">
  <button type="button" class="btn btn-success">LEARN MORE ABOUT SCATTER TOOLTIP PLOT!!</button>
</a>