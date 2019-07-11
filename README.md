# dpeges
Simple React implementation of `dpeges` indicators.
DPE : Diagnostic de performance énergétique (Energy Performance Diagnostic)
GES : Gaz à effet de serre (Greenhouse Gas Emissions)

# References
This works is a porting of the `dpeges` indicators by `pascalz` (https://github.com/pascalz/dpeges)

# Getting started
## Import the components
```javascript
import { DPE, GES } from './dpegesComponent';
```

## Use them with numerical values
```javascript
<DPE value={200} />
<GES value={200} />
```

## Use them with labels
```javascript
<DPE value={'A'} />       // possible standard values are: 'A', 'B', 'C', 'D', 'E', 'F'
<GES value={'A'} />       // same
```

## All options

Option name   | Description                                                     | Required | Default value
------------- | --------------------------------------------------------------- | -------- | -------------
value         | The DPE or GES actual value, can be an integer or just a letter | No       | 200 
width         | The width of the generated SVG image                            | No       | 250 
height        | The height of the generated SVG image                           | No       | 200 
shadow        | Add shadow to the image                                         | No       | false 
lang          | The language to use (currently supported: 'fr' and 'en')        | No       | 'fr' 


## This work is released under the MIT License, see LICENSE file for more details.
