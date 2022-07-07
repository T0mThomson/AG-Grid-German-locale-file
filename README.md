# German locale file for ag-grid 
German translation for the popular data table script "AG Grid" https://www.ag-grid.com/

## How to use
#### 1. ReactJS
```jsx
import { AgGridReact } from 'ag-grid-react';
// Import locale file
import { AG_GRID_LOCALE_DE } from './AG_GRID_LOCALE_DE'

function Table() {

  return <>
    <div className="ag-theme-alpine" style={{ height: "100%", width: "100%" }}>
    
      <AgGridReact
        ...
        // Set the locale text property
        localeText={AG_GRID_LOCALE_DE}
      />
      
    </div>
  </>
  
}

export default Table
```
