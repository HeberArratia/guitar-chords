# Guitar Chords

Basic Guitar Chords http://heberarratia.github.io/guitar-chords/

## Basic operation ##

### HTML ###

for buttons, the chord specified in the div ID

```html
<span id="C" class="btn">Mayor</span>
<span id="C#" class="btn btnsos">#</span>
```

the neck of the guitar is built with a table (see index.html)

```html
<table>
		<tr>
			<td>...</td>
		</tr>
</table>
```
### CSS ###

basic to build the guitar neck (see styles.css)

```css
table{
  ...
}
```

### JavaScript ###

chords are specified in a json

```javascript
{
  "C":["Ex","A3","D2","G0","B1","e0"],
  "C#":["Ex","A4","D6","G6","B6","e4"],
  "Cm":["Ex","A3","D5","G5","B4","e3"],
  "Cm#":["Ex","A4","D6","G6","B5","e4"],
  "D":["Ex","Ax","D0","G2","B3","e2"],
  "D#":["Ex","A6","D8","G8","B8","e6"],
  "Dm":["Ex","Ax","D0","G2","B3","e1"],
  "Dm#":["Ex","A6","D8","G8","B7","e6"],
  "E":["E0","A2","D2","G1","B0","e0"],
  "Em":["E0","A2","D2","G0","B0","e0"],
  "F":["E1","A3","D3","G2","B1","e1"],
  "F#":["E2","A4","D4","G3","B2","e2"],
  "Fm":["E1","A3","D3","G1","B1","e1"],
  "Fm#":["E2","A4","D4","G2","B2","e2"],
  "G":["E3","A2","D0","G0","B3","e3"],
  "G#":["E4","A6","D6","G5","B4","e4"],
  "Gm":["E3","A5","D5","G3","B3","e3"],
  "Gm#":["E4","A6","D6","G4","B4","e4"],
  "A":["Ex","A0","D2","G2","B2","e0"],
  "A#":["Ex","A1","D3","G3","B3","e1"],
  "Am":["Ex","A0","D2","G2","B1","e0"],
  "Am#":["Ex","A1","D3","G3","B2","e1"],
  "B":["Ex","A2","D4","G4","B4","e2"],
  "Bm":["Ex","A2","D4","G4","B3","e2"]
};
```
## Developer ##

[@heberarratia](heberarratia.github.io)
