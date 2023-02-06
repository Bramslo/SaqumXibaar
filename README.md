
# SAQUM XIBAAR

A module to manage the information of a user residing in Senegal, such as his region, his department, his telephone number, and currency formatting functions and so on and so forth

## Sources
- https://en.wikipedia.org/wiki/Senegal
- https://developer.mozilla.org/en-US/docs/Web/JavaScript
- https://developer.mozilla.org/en-US/docs/Web/CSS
- http://es6-features.org/#Constants

## Features

- Region and department selection
- Format input and output currency amount to XOF
- Format Telephone Number
- Geolocalisation Adress

## Region and departments
 
    #### 14 Regions
    [
        Dakar,Diourbel,Fatick,Kaffrine,Kaolack,Kedougou,kolda,Louga,Matam,Daint-Louis,Sedhiou,Tambacounda,Thies,Ziguinchor
    ]
    #### 45 Departments
    [
        - DAKAR (5) : Dakar,Guediawaye,Pikine,Rufisque,Keur  <14.75, -17.333333>
        Masar
        - DIOURBEL (3) : Bambey,Diourbel,Mbacke <14.75, -16.25> 
        - FATICK (3) : Fatick,Foundiougne,Gossas <14.366667, -16.133333>
        - KAFFRINE (4) : Birkilane,Kaffrine,Koungheul,Malem Hoddar <14.116667, -15.7>
        - KAOLACK (3) : Guinguineo,Kaolack,Nioro du Rip <14.15, -14.5>
        - KEDOUGOU (3) : Kedougou,Salemata,Saraya <12.55, -12.183333>

    ]
    #### 113 Districts


## Installation

Install saqumXibaar with npm

```bash
  npm install saqumXibaar
  cd saqumXibaar
```
    
## Usage/Examples

```javascript
import Component from 'saqumXibaar'

function App() {
  return <Component />
}
```

