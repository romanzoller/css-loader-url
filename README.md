# Build

```
npm install
npm run build
```

## Output

```
.red-square {
  content: url(red dot.png);
  width: 100px;
  height: 100px;
}
```

## Expected Output

```
.red-square {
  content: url("red dot.png");
  width: 100px;
  height: 100px;
}
```
