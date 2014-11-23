library verilog;
use verilog.vl_types.all;
entity true_dual_port_ram_single_clock is
    generic(
        DATA_WIDTH      : integer := 8;
        ADDR_WIDTH      : integer := 6
    );
    port(
        data_a          : in     vl_logic_vector;
        data_b          : in     vl_logic_vector;
        addr_a          : in     vl_logic_vector;
        addr_b          : in     vl_logic_vector;
        we_a            : in     vl_logic;
        we_b            : in     vl_logic;
        clk             : in     vl_logic;
        q_a             : out    vl_logic_vector;
        q_b             : out    vl_logic_vector
    );
    attribute mti_svvh_generic_type : integer;
    attribute mti_svvh_generic_type of DATA_WIDTH : constant is 1;
    attribute mti_svvh_generic_type of ADDR_WIDTH : constant is 1;
end true_dual_port_ram_single_clock;
