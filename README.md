# TimeWith media queries

To use with glamorous / glamor

## Install

```bash
$ yarn add @time-with/media-queries
```

## Usage
    
    // to use with glamorous
    import glamorous from 'glamorous'
    import { tablet_max } from '@time-with/media-queries'
    
    const MyDiv = glamorous.div({
      padding: 40,
      [tablet_max]: { padding: 30 },
    })
    
    <MyDiv>Hello World</MyDiv>

## License

MIT
