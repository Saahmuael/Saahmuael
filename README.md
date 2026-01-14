# Hello! 👋 

```systemverilog
module Samuel # (
    parameter string PRONOUNS   =   "He/Him",
    parameter string SCHOOL     =   "University of Waterloo",
    parameter string PROGRAM    =   "Computer Engineering"
)();
    string languages[], hardware[], bus_fabrics[], tools[], learnings[];
    string fun_fact;

    initial begin
        //Some things I know:
        languages    = '{"Verilog", "SystemVerilog", 
                         "C/C++", "Python"};

        hardware     = '{"Peripherals (PWM, Encryption)", 
                         "Memory Devices", "RISC-V"};

        bus_fabrics  = '{"APB", "AXI-4", 
                         "UART", "SPI", 
                         "VGA", "I2C"};
                        
        tools        = '{"Verilator", "Cocotb", 
                         "Vivado", "Yosys", "GTKWave"};

        //Things I am learning:
        learnings    = '{"Ethernet", "AXI CHI", 
                         "Caches", "DDR Interfaces", "UVM"};
        //Others:
        fun_fact = "My Username, \"Saahmuael\" comes from an old nickname I had in school";
    end

endmodule
```
