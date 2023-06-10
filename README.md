# version 1.0.4

```
npm i keyboard-emoji-meaning
```

### Get All Emoji

```javascript
import emoji from 'keyboard-emoji-meaning'

console.log(emoji.allEmoji)

// {
//   'smileys & people': [
//     { emoji: '😀', meaning: 'Grinning Face' },
//     { emoji: '😃', meaning: 'Grinning Face with Big Eyes' },
//     { emoji: '😄', meaning: 'Grinning Face with Smiling Eyes' },
//     { emoji: '😁', meaning: 'Beaming Face with Smiling Eyes' },
//     { emoji: '😆', meaning: 'Grinning Squinting Face' },
//     { emoji: '😅', meaning: 'Grinning Face with Sweat' },
//     { emoji: '🤣', meaning: 'Rolling on the Floor Laughing' },
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//}

```


### Get specific emoji

| Value            |
| :--------------- |
| smileys & people |
| travel & places  |
| food & drink     |
| animals & nature |
| activity         |
| flags            |
| objects          |
| symbols          |



```javascript
import emoji from 'keyboard-emoji-meaning'



console.log(emoji.emoji('activity'))

// [
//   { emoji: '🕴️' , meaning: 'Person in Suit Levitating' },
//   { emoji: '🧗', meaning: 'Person Climbing' },
//   { emoji: '🧗‍♂️', meaning: 'Man Climbing' },
//   { emoji: '🧗‍♀️', meaning: 'Woman Climbing' },
//   { emoji: '🤺', meaning: 'Person Fencing' },
//   { emoji: '🏇', meaning: 'Horse Racing' },
//   { emoji: '⛷️', meaning: 'Skier' },
//   { emoji: '🏂', meaning: 'Snowboarder' },
//   { emoji: '🏌️' , meaning: 'Person Golfing' },
//   { emoji: '🏌️‍♂️' , meaning: 'Man Golfing' },
//   { emoji: '🏌️‍♀️' , meaning: 'Woman Golfing' },
//   { emoji: '🏄', meaning: 'Person Surfing' },
//   { emoji: '🏄‍♂️', meaning: 'Man Surfing' },
//   { emoji: '🏄‍♀️', meaning: 'Woman Surfing' },
//   { emoji: '🚣', meaning: 'Person Rowing Boat' },        
//   { emoji: '🚣‍♂️', meaning: 'Man Rowing Boat' },        
//   { emoji: '🚣‍♀️', meaning: 'Woman Rowing Boat' },      
//   { emoji: '🏊', meaning: 'Person Swimming' },
//   { emoji: '🏊‍♂️', meaning: 'Man Swimming' },
//   { emoji: '🏊‍♀️', meaning: 'Woman Swimming' },
//   { emoji: '⛹️', meaning: 'Person Bouncing Ball' },      
//   { emoji: '⛹️‍♂️', meaning: 'Man Bouncing Ball' },      
//   { emoji: '⛹️‍♀️', meaning: 'Woman Bouncing Ball' },    
//   { emoji: '🏋️' , meaning: 'Person Lifting Weights' },   
//   { emoji: '🏋️‍♂️' , meaning: 'Man Lifting Weights' },   
//   { emoji: '🏋️‍♀️' , meaning: 'Woman Lifting Weights' }, 
//   { emoji: '🚴', meaning: 'Person Biking' },
//   { emoji: '🚴‍♂️', meaning: 'Man Biking' },
//   { emoji: '🚴‍♀️', meaning: 'Woman Biking' },
//   { emoji: '🚵', meaning: 'Person Mountain Biking' },
//   { emoji: '🚵‍♂️', meaning: 'Man Mountain Biking' },
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//   ----------------------------------------------------------------
//]

```
