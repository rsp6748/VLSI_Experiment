entity half_add is
    Port ( a : in STD_LOGIC;
           b : in STD_LOGIC;
           s : out STD_LOGIC;
           c : out STD_LOGIC);
end half_add;

architecture Behavioral of half_add is
component and1
Port ( a : in STD_LOGIC;
           b : in STD_LOGIC;
           c : out STD_LOGIC);
end component;
component xor1
Port ( a : in STD_LOGIC;
           b : in STD_LOGIC;
           c : out STD_LOGIC);
end component;
           

begin
h1: xor1 port map(a,b,s);
h2: and1 port map(a,b,c);


end Behavioral;
