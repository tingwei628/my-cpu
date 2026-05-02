# 1. 編譯
iverilog -o exercises/and_gate/build/and_gate.vvp exercises/and_gate/and_gate.v exercises/and_gate/and_gate_tb.v

# 2. 模擬
vvp exercises/and_gate/build/and_gate.vvp

# 3. 看波形
gtkwave exercises/and_gate/build/and_gate.vcd