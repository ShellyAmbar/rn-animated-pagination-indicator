- An animated dots effect of a pagination view.

- It comes with a built-in TypeScript typings and is compatible with all popular JavaScript frameworks. You can use it directly or leverage well-maintained wrapper packages that allow for a more native integration with your frameworks of choice.

# Example:

![](./assets/videos/1.gif)

## How to use:

- remember to put overflow: "hidden" on the outher view.

```

  <PaginationIndicator data={data} scrollX={scrollX} screenWidth={width} />
</>
```

## PaginationIndicator Props

| Name                  | Type           | Default |
| --------------------- | -------------- | ------- |
| data                  | any[]          |
| scrollX               | Animated.Value |
| screenWidth           | number         |
| dotWidthOutputRange   | number[]       |
| dotOpacityOutputRange | number[]       |
| dotStyle              | ViewStyle      |
| containerStyle        | ViewStyle      |
