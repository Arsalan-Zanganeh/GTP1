# GTP1

| Type                           | Name                                 | Needs Initial Value | Reference                                             | Location | first line of similiar def/use |
|--------------------------------|--------------------------------------|---------------------|-------------------------------------------------------|----------|--------------------------------|
| #include                       | gro_gtp_<tcp/udp>4.h                 | No                  | rte_gro.c > gro_gtp_<tcp/udp>4.h                      | lib/gro/ | 11                             |
| static gro_tbl_create_fn       | gro_gtp_<tcp/udp>4_tbl_create        | No                  | rte_gro.c                                             | lib/gro/ | 23                             |
| static gro_tbl_destroy_fn      | gro_gtp_<tcp/udp>4_tbl_destroy       | No                  | rte_gro.c                                             | lib/gro/ | 26                             |
| static gro_tbl_pkt_count_fn    | gro_gtp_<tcp/udp>4_tbl_pkt_count     | No                  | rte_gro.c                                             | lib/gro/ | 31                             |
| #define                        | IS_IPV4_GTP_<TCP/UDP>4_PKT           | Yes                 | rte_gro.c > rte_gro.h > rte_mbuf.h > rte_mbuf_ptype.h | lib/gro/ | 37                             |
| struct gro_gtp_<tcp/udp>4_tbl  | gtp_<tcp/udp>_tbl                    | No                  | rte_gro.c > gro_gtp_<tcp/udp>4.h                      | lib/gro/ | 161                            |
| struct gro_gtp_<tcp/udp>4_flow | gtp_<tcp/udp>_flows                  | No                  | rte_gro.c > gro_gtp_<tcp/udp>4.h                      | lib/gro/ | 162                            |
| struct gro_gtp_<tcp/udp>4_item | gtp_<tcp/udp>_items                  | Yes                 | rte_gro.c > gro_gtp_<tcp/udp>4.h                      | lib/gro/ | 163                            |
| uint8_t                        | do_gtp_<tcp/udp>_gro                 | No                  | rte_gro.c                                             | lib/gro/ | 189                            |
| if parenthesis                 | RTE_GRO_IPV4_GTP_<TCP/UDP>_IPV4      | No                  | rte_gro.c > rte_gro.h                                 | lib/gro/ | 192                            |
| if pseducode                   |                                      | No                  | rte_gro.c                                             | lib/gro/ | 203                            |
| else if pseducode              |                                      | No                  | rte_gro.c                                             | lib/gro/ | 273                            |
| if pseducode                   | gro_gtp_<tcp/udp>4_tbl_timeout_flush | No                  | rte_gro.c > gro_gtp_<tcp/udp>4.h                      | lib/gro/ | 325                            |
| void *                         | gtp_<tcp/udp>_tbl                    | No                  | rte_gro.c                                             | lib/gro/ | 362                            |
| uint8_t                        | do_gtp_<tcp/udp>_gro                 | No                  | rte_gro.c                                             | lib/gro/ | 365                            |
| if parenthesis                 | RTE_GRO_IPV4_GTP_<TCP/UDP>_IPV4      | No                  | rte_gro.c > rte_gro.h                                 | lib/gro/ | 367                            |
| struct gro_gtp_<tcp/udp>4_tbl  | gtp_<tcp/udp>_tbl                    | No                  | rte_gro.c > gro_gtp_<tcp/udp>4.h                      | lib/gro/ | 373                            |
| else if pseducode              |                                      | No                  | rte_gro.c                                             | lib/gro/ | 392                            |
| if pseducode                   |                                      | No                  | rte_gro.c                                             | lib/gro/ | 440                            |




