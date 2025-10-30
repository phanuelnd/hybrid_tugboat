=== Dataset: Integrated OSG + DAT Cleaned ===
📄 Shape: (11520, 80)
📝 Columns and types:
Unnamed: 0                            object
M/E PORT - Raw Supply Flowrate       float64
M/E PORT - Raw Supply Total Fuel     float64
M/E PORT - Raw Supply Temperature    float64
M/E PORT - Raw Return Flowrate       float64
                                      ...
Energy_STBD_kWh                      float64
RPM_PORT                             float64
RPM_STBD                             float64
LC2_PORT_Oxygen_PORT                 float64
LC2_STBD_Oxygen_STBD                 float64
Length: 80, dtype: object

🔹 First 5 rows:
            Unnamed: 0  M/E PORT - Raw Supply Flowrate  
0  2025-07-13 00:00:00                             0.0
1  2025-07-13 00:01:00                             0.0
2  2025-07-13 00:02:00                             0.0
3  2025-07-13 00:03:00                             0.0
4  2025-07-13 00:04:00                             0.0

   M/E PORT - Raw Supply Total Fuel  M/E PORT - Raw Supply Temperature  
0                      3.735579e+08                          43.600006
1                      3.735579e+08                          43.598339
2                      3.735579e+08                          43.600006
3                      3.735579e+08                          43.600006
4                      3.735579e+08                          43.600006

   M/E PORT - Raw Return Flowrate  M/E PORT - Raw Return Total Fuel  
0                             0.0                      3.258233e+08
1                             0.0                      3.258233e+08
2                             0.0                      3.258233e+08
3                             0.0                      3.258233e+08
4                             0.0                      3.258233e+08

   M/E PORT - Raw Return Temperature  M/E PORT - Flow Rate  
0                          43.200012                   0.0
1                          43.200012                   0.0
2                          43.185011                   0.0
3                          43.111673                   0.0
4                          43.100006                   0.0

   M/E PORT - Total Fuel  M/E PORT - Temperature  ...  Torque_PORT_kN*m  
0            47734651.32               43.600006  ...               0.0
1            47734651.32               43.598339  ...               0.0
2            47734651.32               43.600006  ...               0.0
3            47734651.32               43.600006  ...               0.0
4            47734651.32               43.600006  ...               0.0

   Torque_STBD_kN*m  Power_PORT_kW  Energy_Port_kWh  Power_STBD_kW  
0               0.0            0.0              0.0            0.0
1               0.0            0.0              0.0            0.0
2               0.0            0.0              0.0            0.0
3               0.0            0.0              0.0            0.0
4               0.0            0.0              0.0            0.0

   Energy_STBD_kWh  RPM_PORT  RPM_STBD  LC2_PORT_Oxygen_PORT  
0              0.0       0.0       0.0                   0.0
1              0.0       0.0       0.0                   0.0
2              0.0       0.0       0.0                   0.0
3              0.0       0.0       0.0                   0.0
4              0.0       0.0       0.0                   0.0

   LC2_STBD_Oxygen_STBD
0                   0.0
1                   0.0
2                   0.0
3                   0.0
4                   0.0

[5 rows x 80 columns]

🔹 Summary statistics for numeric columns:
       M/E PORT - Raw Supply Flowrate  M/E PORT - Raw Supply Total Fuel  
count                    11520.000000                      1.152000e+04
mean                     15175.162757                      3.748868e+08
std                      29808.879420                      9.302094e+05
min                          0.000000                      3.735579e+08
25%                          0.000000                      3.741335e+08
50%                          0.000000                      3.746708e+08
75%                          0.000000                      3.758967e+08
max                     123481.816166                      3.764741e+08

    M/E PORT - Raw Supply Temperature  M/E PORT - Raw Return Flowrate
count                       11520.000000                    11520.000000
mean                           36.680224                    12904.600130
std                             4.672592                    24662.646411
min                            26.721680                        0.000000
25%                            33.800018                        0.000000
50%                            37.876666                        0.000000
75%                            40.302101                        0.000000
max                            45.600006                    82989.817260

    M/E PORT - Raw Return Total Fuel  M/E PORT - Raw Return Temperature
count                      1.152000e+04                       11520.000000
mean                       3.269527e+08                          42.838011
std                        7.884551e+05                           5.874910
min                        3.258233e+08                          32.700012
25%                        3.263080e+08                          38.300018
50%                        3.267770e+08                          41.000000
75%                        3.278087e+08                          47.603341
max                        3.283030e+08                          59.411672

    M/E PORT - Flow Rate  M/E PORT - Total Fuel  M/E PORT - Temperature
count          11520.000000           1.152000e+04            11520.000000
mean              18.921355           4.793412e+07               36.680224
std               50.391839           1.418547e+05                4.672592
min              -42.014495           4.773465e+07               26.721680
25%                0.000000           4.782554e+07               33.800018
50%                0.000000           4.789379e+07               37.876666
75%                0.000000           4.808804e+07               40.302101
max              412.655158           4.817115e+07               45.600006

    M/E PORT - Error  ...  Torque_PORT_kN*m  Torque_STBD_kN*m  
count           11520.0  ...      11520.000000      11520.000000
mean                0.0  ...          0.470295          0.645729
std                 0.0  ...          1.245914          1.439966
min                 0.0  ...          0.000000          0.000000
25%                 0.0  ...          0.000000          0.000000
50%                 0.0  ...          0.000000          0.000000
75%                 0.0  ...          0.000000          0.000000
max                 0.0  ...          8.800000          8.900000

    Power_PORT_kW  Energy_Port_kWh  Power_STBD_kW  Energy_STBD_kWh
count   11520.000000     11520.000000   11520.000000     11520.000000
mean       53.845174         0.897420      72.847526         1.214125
std       169.234844         2.820581     190.853122         3.180885
min         0.000000         0.000000       0.000000         0.000000
25%         0.000000         0.000000       0.000000         0.000000
50%         0.000000         0.000000       0.000000         0.000000
75%         0.000000         0.000000       0.000000         0.000000
max      1429.000000        23.816667    1417.700000        23.628333

    RPM_PORT      RPM_STBD  LC2_PORT_Oxygen_PORT  LC2_STBD_Oxygen_STBD
count  11520.000000  11520.000000               11520.0               11520.0
mean     160.206146    206.702166                   0.0                   0.0
std      369.061073    406.500639                   0.0                   0.0
min        0.000000      0.000000                   0.0                   0.0
25%        0.000000      0.000000                   0.0                   0.0
50%        0.000000      0.000000                   0.0                   0.0
75%        0.000000      0.000000                   0.0                   0.0
max     1670.700000   1650.800000                   0.0                   0.0

[8 rows x 76 columns]

=== Dataset: DAT 1-Min Resampled ===
📄 Shape: (11520, 56)
📝 Columns and types:
Unnamed: 0                             object
M/E PORT - Raw Supply Flowrate        float64
M/E PORT - Raw Supply Total Fuel      float64
M/E PORT - Raw Supply Temperature     float64
M/E PORT - Raw Return Flowrate        float64
M/E PORT - Raw Return Total Fuel      float64
M/E PORT - Raw Return Temperature     float64
M/E PORT - Flow Rate                  float64
M/E PORT - Total Fuel                 float64
M/E PORT - Temperature                float64
M/E PORT - Error                      float64
M/E STBD - Raw Supply Flowrate        float64
M/E STBD - Raw Supply Total Fuel      float64
M/E STBD - Raw Supply Temperature     float64
M/E STBD - Raw Return Flowrate        float64
M/E STBD - Raw Return Total Fuel      float64
M/E STBD - Raw Return Temperature     float64
M/E STBD - Flow Rate                  float64
M/E STBD - Total Fuel                 float64
M/E STBD - Temperature                float64
M/E STBD - Error                      float64
Shipboard GPS - SOG                   float64
Shipboard GPS - Latitude              float64
Shipboard GPS - Longitude             float64
Shipboard GPS - Error                 float64
Shipboard AIS - Dimension to Stbd     float64
Shipboard AIS - Dimension to Port     float64
Shipboard AIS - Dimension to Stern    float64
Shipboard AIS - Dimension to Bow      float64
Shipboard AIS - MMSI                  float64
Shipboard AIS - Nearest Ship SOG      float64
Shipboard AIS - Latitude              float64
Shipboard AIS - Longitude             float64
Shipboard AIS - Error                 float64
LC-2 PORT - Raw Lambda                float64
LC-2 PORT - Oxygen PORT               float64
LC-2 PORT - Error                     float64
LC-2 STBD - Raw Lambda                float64
LC-2 STBD - Oxygen STBD               float64
LC-2 STBD - Error                     float64
Shaft PORT - Gauge Reading            float64
Shaft PORT - Battery Level            float64
Shaft PORT - RX Power                 float64
Shaft PORT - RPM                      float64
Shaft PORT - Torque                   float64
Shaft PORT - Power                    float64
Shaft PORT - Energy                   float64
Shaft PORT - Error                    float64
Shaft STBD - Gauge Reading            float64
Shaft STBD - Battery Level            float64
Shaft STBD - RX Power                 float64
Shaft STBD - RPM                      float64
Shaft STBD - Torque                   float64
Shaft STBD - Power                    float64
Shaft STBD - Energy                   float64
Shaft STBD - Error                    float64
dtype: object

🔹 First 5 rows:
            Unnamed: 0  M/E PORT - Raw Supply Flowrate  
0  2025-07-13 00:00:00                             0.0
1  2025-07-13 00:01:00                             0.0
2  2025-07-13 00:02:00                             0.0
3  2025-07-13 00:03:00                             0.0
4  2025-07-13 00:04:00                             0.0

   M/E PORT - Raw Supply Total Fuel  M/E PORT - Raw Supply Temperature  
0                      3.735579e+08                          43.600006
1                      3.735579e+08                          43.598339
2                      3.735579e+08                          43.600006
3                      3.735579e+08                          43.600006
4                      3.735579e+08                          43.600006

   M/E PORT - Raw Return Flowrate  M/E PORT - Raw Return Total Fuel  
0                             0.0                      3.258233e+08
1                             0.0                      3.258233e+08
2                             0.0                      3.258233e+08
3                             0.0                      3.258233e+08
4                             0.0                      3.258233e+08

   M/E PORT - Raw Return Temperature  M/E PORT - Flow Rate  
0                          43.200012                   0.0
1                          43.200012                   0.0
2                          43.185011                   0.0
3                          43.111673                   0.0
4                          43.100006                   0.0

   M/E PORT - Total Fuel  M/E PORT - Temperature  ...  Shaft PORT - Energy  
0            47734651.32               43.600006  ...                  0.0
1            47734651.32               43.598339  ...                  0.0
2            47734651.32               43.600006  ...                  0.0
3            47734651.32               43.600006  ...                  0.0
4            47734651.32               43.600006  ...                  0.0

   Shaft PORT - Error  Shaft STBD - Gauge Reading  Shaft STBD - Battery Level  
0                 0.0                         0.0                 3393.733333
1                 0.0                         0.0                 3392.666667
2                 0.0                         0.0                 3395.066667
3                 0.0                         0.0                 3395.400000
4                 0.0                         0.0                 3393.566667

   Shaft STBD - RX Power  Shaft STBD - RPM  Shaft STBD - Torque  
0             -49.166667               0.0                  0.0
1             -49.850000               0.0                  0.0
2             -49.700000               0.0                  0.0
3             -48.966667               0.0                  0.0
4             -50.150000               0.0                  0.0

   Shaft STBD - Power  Shaft STBD - Energy  Shaft STBD - Error
0                 0.0                  0.0                 0.0
1                 0.0                  0.0                 0.0
2                 0.0                  0.0                 0.0
3                 0.0                  0.0                 0.0
4                 0.0                  0.0                 0.0

[5 rows x 56 columns]

🔹 Summary statistics for numeric columns:
       M/E PORT - Raw Supply Flowrate  M/E PORT - Raw Supply Total Fuel  
count                    11520.000000                      1.152000e+04
mean                     15175.162757                      3.748868e+08
std                      29808.879420                      9.302094e+05
min                          0.000000                      3.735579e+08
25%                          0.000000                      3.741335e+08
50%                          0.000000                      3.746708e+08
75%                          0.000000                      3.758967e+08
max                     123481.816166                      3.764741e+08

    M/E PORT - Raw Supply Temperature  M/E PORT - Raw Return Flowrate
count                       11520.000000                    11520.000000
mean                           36.680224                    12904.600130
std                             4.672592                    24662.646411
min                            26.721680                        0.000000
25%                            33.800018                        0.000000
50%                            37.876666                        0.000000
75%                            40.302101                        0.000000
max                            45.600006                    82989.817260

    M/E PORT - Raw Return Total Fuel  M/E PORT - Raw Return Temperature
count                      1.152000e+04                       11520.000000
mean                       3.269527e+08                          42.838011
std                        7.884551e+05                           5.874910
min                        3.258233e+08                          32.700012
25%                        3.263080e+08                          38.300018
50%                        3.267770e+08                          41.000000
75%                        3.278087e+08                          47.603341
max                        3.283030e+08                          59.411672

    M/E PORT - Flow Rate  M/E PORT - Total Fuel  M/E PORT - Temperature
count          11520.000000           1.152000e+04            11520.000000
mean              18.921355           4.793412e+07               36.680224
std               50.391839           1.418547e+05                4.672592
min              -42.014495           4.773465e+07               26.721680
25%                0.000000           4.782554e+07               33.800018
50%                0.000000           4.789379e+07               37.876666
75%                0.000000           4.808804e+07               40.302101
max              412.655158           4.817115e+07               45.600006

    M/E PORT - Error  ...  Shaft PORT - Energy  Shaft PORT - Error
count           11520.0  ...         11520.000000        11520.000000
mean                0.0  ...             1.814030        28055.109009
std                 0.0  ...             5.654361       113905.079806
min                 0.0  ...             0.000000            0.000000
25%                 0.0  ...             0.000000            0.000000
50%                 0.0  ...             0.000000            0.000000
75%                 0.0  ...             0.000000            0.000000
max                 0.0  ...            47.808238       503733.066667

    Shaft STBD - Gauge Reading  Shaft STBD - Battery Level
count                11520.000000                11520.000000
mean                -30218.425621                 3377.952226
std                  67121.046454                   30.198546
min                -412705.150000                 3252.133333
25%                      0.000000                 3353.870833
50%                      0.000000                 3383.925000
75%                      0.000000                 3397.300000
max                  15077.800000                 3454.716667

    Shaft STBD - RX Power  Shaft STBD - RPM  Shaft STBD - Torque
count           11520.000000      11520.000000         11520.000000
mean              -50.559699        207.377833             0.651671
std                 2.472554        407.201107             1.446781
min               -59.550000          0.000000             0.000000
25%               -51.516667          0.000000             0.000000
50%               -49.716667          0.000000             0.000000
75%               -48.833333          0.000000             0.000000
max               -45.422680       1651.161666             8.897026

    Shaft STBD - Power  Shaft STBD - Energy  Shaft STBD - Error
count        11520.000000         11520.000000        11520.000000
mean            73.688471             2.456282           56.115981
std            191.365153             6.378838         3451.175835
min              0.000000             0.000000            0.000000
25%              0.000000             0.000000            0.000000
50%              0.000000             0.000000            0.000000
75%              0.000000             0.000000            0.000000
max           1421.909841            47.396992       260262.083333

[8 rows x 55 columns]

=== Dataset: Port Mission Stats ===
📄 Shape: (54, 8)
📝 Columns and types:
Port_mission          int64
start_time           object
end_time             object
duration_minutes      int64
total_energy        float64
total_fuel          float64
fuel_per_energy     float64
mean_temp           float64
dtype: object

🔹 First 5 rows:
   Port_mission           start_time             end_time  duration_minutes  
0             1  2025-07-13 04:12:00  2025-07-13 06:44:00               153
1             2  2025-07-13 20:35:00  2025-07-13 21:46:00                72
2             3  2025-07-13 21:48:00  2025-07-13 21:51:00                 4
3             4  2025-07-14 03:29:00  2025-07-14 04:44:00                76
4             5  2025-07-14 04:47:00  2025-07-14 04:48:00                 2

   total_energy    total_fuel  fuel_per_energy  mean_temp
0    532.234993  7.304847e+09     1.372485e+07  29.206771
1    484.386670  3.438877e+09     7.099447e+06  28.318361
2      0.491667  1.910781e+08     3.886331e+08  28.776257
3    312.341672  3.630807e+09     1.162447e+07  29.076058
4      0.278334  9.556041e+07     3.433300e+08  29.200012

🔹 Summary statistics for numeric columns:
       Port_mission  duration_minutes  total_energy    total_fuel  
count     54.000000         54.000000     54.000000  5.400000e+01
mean      27.500000         36.462963    191.384382  1.747763e+09
std       15.732133         50.328623    322.853327  2.411374e+09
min        1.000000          1.000000      0.101667  4.788437e+07
25%       14.250000          2.000000      0.260001  9.578064e+07
50%       27.500000         12.000000     45.124166  5.778623e+08
75%       40.750000         54.000000    196.836250  2.599106e+09
max       54.000000        231.000000   1604.209998  1.106765e+10

    fuel_per_energy  mean_temp
count     5.400000e+01  54.000000
mean      1.401853e+08  30.051521
std       1.807679e+08   1.868372
min       3.490284e+06  27.825563
25%       8.976966e+06  28.884290
50%       1.940318e+07  29.835682
75%       3.640586e+08  30.772768
max       4.721543e+08  36.783339

=== Dataset: STBD Mission Stats ===
📄 Shape: (22, 8)
📝 Columns and types:
STBD_mission          int64
start_time           object
end_time             object
duration_minutes      int64
total_energy        float64
total_fuel          float64
fuel_per_energy     float64
mean_temp           float64
dtype: object

🔹 First 5 rows:
   STBD_mission           start_time             end_time  duration_minutes  
0             1  2025-07-13 04:12:00  2025-07-13 06:45:00               154
1             2  2025-07-13 20:35:00  2025-07-13 21:51:00                77
2             3  2025-07-14 03:29:00  2025-07-14 04:49:00                81
3             4  2025-07-14 12:31:00  2025-07-14 14:08:00                98
4             5  2025-07-14 18:36:00  2025-07-14 20:25:00               110

   total_energy    total_fuel  fuel_per_energy  mean_temp
0    548.763329  9.431852e+09     1.718747e+07  28.361317
1    491.356665  4.717425e+09     9.600817e+06  27.696803
2    312.630002  4.963476e+09     1.587652e+07  28.520625
3    448.974996  6.006911e+09     1.337917e+07  28.376231
4    928.448340  6.744400e+09     7.264163e+06  29.102915

🔹 Summary statistics for numeric columns:
       STBD_mission  duration_minutes  total_energy    total_fuel  
count     22.000000         22.000000     22.000000  2.200000e+01
mean      11.500000        116.818182    635.738939  7.180862e+09
std        6.493587         79.520968    690.486904  4.887082e+09
min        1.000000         32.000000    141.740001  1.963049e+09
25%        6.250000         78.000000    315.545834  4.778938e+09
50%       11.500000         98.500000    509.009997  6.039686e+09
75%       16.750000        138.750000    661.489584  8.544320e+09
max       22.000000        413.000000   3496.173336  2.537898e+10

    fuel_per_energy  mean_temp
count     2.200000e+01  22.000000
mean      1.361464e+07  28.764871
std       4.269601e+06   0.904980
min       7.259074e+06  27.499428
25%       1.091304e+07  28.003291
50%       1.334508e+07  28.555983
75%       1.550638e+07  29.592619
max       2.469097e+07  30.456029

=== Dataset: Mission Summary Table ===
📄 Shape: (1, 12)
📝 Columns and types:
Port_total_missions           int64
Port_avg_duration_min       float64
Port_total_energy_kWh       float64
Port_total_fuel_L           float64
Port_avg_fuel_per_energy    float64
Port_avg_temp_C             float64
STBD_total_missions           int64
STBD_avg_duration_min       float64
STBD_total_energy_kWh       float64
STBD_total_fuel_L           float64
STBD_avg_fuel_per_energy    float64
STBD_avg_temp_C             float64
dtype: object

🔹 First 5 rows:
   Port_total_missions  Port_avg_duration_min  Port_total_energy_kWh  
0                   54              36.462963            10334.75665

   Port_total_fuel_L  Port_avg_fuel_per_energy  Port_avg_temp_C  
0       9.437919e+10              1.401853e+08        30.051521

   STBD_total_missions  STBD_avg_duration_min  STBD_total_energy_kWh  
0                   22             116.818182            13986.25666

   STBD_total_fuel_L  STBD_avg_fuel_per_energy  STBD_avg_temp_C
0       1.579790e+11              1.361464e+07        28.764871

🔹 Summary statistics for numeric columns:
       Port_total_missions  Port_avg_duration_min  Port_total_energy_kWh  
count                  1.0               1.000000                1.00000
mean                  54.0              36.462963            10334.75665
std                    NaN                    NaN                    NaN
min                   54.0              36.462963            10334.75665
25%                   54.0              36.462963            10334.75665
50%                   54.0              36.462963            10334.75665
75%                   54.0              36.462963            10334.75665
max                   54.0              36.462963            10334.75665

    Port_total_fuel_L  Port_avg_fuel_per_energy  Port_avg_temp_C
count       1.000000e+00              1.000000e+00         1.000000
mean        9.437919e+10              1.401853e+08        30.051521
std                  NaN                       NaN              NaN
min         9.437919e+10              1.401853e+08        30.051521
25%         9.437919e+10              1.401853e+08        30.051521
50%         9.437919e+10              1.401853e+08        30.051521
75%         9.437919e+10              1.401853e+08        30.051521
max         9.437919e+10              1.401853e+08        30.051521

    STBD_total_missions  STBD_avg_duration_min  STBD_total_energy_kWh
count                  1.0               1.000000                1.00000
mean                  22.0             116.818182            13986.25666
std                    NaN                    NaN                    NaN
min                   22.0             116.818182            13986.25666
25%                   22.0             116.818182            13986.25666
50%                   22.0             116.818182            13986.25666
75%                   22.0             116.818182            13986.25666
max                   22.0             116.818182            13986.25666

    STBD_total_fuel_L  STBD_avg_fuel_per_energy  STBD_avg_temp_C
count       1.000000e+00              1.000000e+00         1.000000
mean        1.579790e+11              1.361464e+07        28.764871
std                  NaN                       NaN              NaN
min         1.579790e+11              1.361464e+07        28.764871
25%         1.579790e+11              1.361464e+07        28.764871
50%         1.579790e+11              1.361464e+07        28.764871
75%         1.579790e+11              1.361464e+07        28.764871
max         1.579790e+11              1.361464e+07        28.764871
