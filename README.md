# @materialios/hooks
ReactJs hooks for @materialios

## Features
* useWindowSize
* useResponsive

## Installation
```
npm i @materialios/hooks
```

## Example
```c
import { useResponsive } from '@materialios/hooks'

const App = () => {
  const { orientation, device, size } = useResponsive()

  return (
    <div className='App'>
      <p>orientation: {orientation}</p>
      <p>device: {device}</p>
      <p>size: {size}</p>
    </div>
  )
}

export default App
```

## Contributing
It's really still early days. So, help us to grow faster. Email me on [muhammadnurrendra@gmail.com](mailto:muhammadnurrendra@gmail.com)

## Creator
[@mnrendra](https://github.com/mnrendra)
