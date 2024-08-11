# Note
```
guid: u](0D5V&pi
notetype: Basic
```

### Tags
```
```

## Front
Verilog: Guidelines

## Back
1. Use always @ (posedge clk) and nonblocking assignments to model synchronous sequential logic
2. Use continuous assignments to model simple combinational logic
3. Use always @ (*) and blocking assignments to model more complicated combinational logic where the
always statement is helpful
4. Do not make assignments to the same signal in more than one always statement or continuous
assignment statement.
