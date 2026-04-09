# Sample Data Reference

## Table 1: go_carrier_performance_monthly

| summary_id | summary_month | carrier_key | total_shipments_assigned | completed_shipments | cancelled_shipments | completion_rate_percentage | cancellation_rate_percentage | total_distance_covered | average_distance_per_shipment | total_stops_serviced | average_stops_per_shipment | route_efficiency_score | on_time_performance_percentage | carrier_utilization_percentage | load_date | update_date | source_system |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 7 | 2026-02-01 | SDIA | 1 | 0 | 1 | 0.00 | 100.00 | 522.00 | 522.00 | 1 | 1.00 | 100.00 | null | 0.00 | 2026-04-07T12:54:58.617Z | 2026-04-07T12:54:58.617Z | TMS_ORACLE |
| 9 | 2026-02-01 | SNCY | 1 | 0 | 1 | 0.00 | 100.00 | 601.40 | 601.40 | 1 | 1.00 | 100.00 | null | 0.00 | 2026-04-07T12:54:58.617Z | 2026-04-07T12:54:58.617Z | TMS_ORACLE |

---

## Table 2: go_shipment_daily_summary

| summary_id | summary_date | carrier_key | facility_key | total_shipment_count | active_shipment_count | completed_shipment_count | cancelled_shipment_count | reconciled_shipment_count | cancelled_shipment_percentage | reconciled_shipment_percentage | total_route_distance_sum | average_route_distance | total_stops_sum | average_stops_per_shipment | out_of_route_distance_sum | out_of_route_percentage | route_efficiency_index | load_date | update_date | source_system |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 7 | 2025-06-09 | GBEA | CFSGDYR031 | 1 | 0 | 1 | 0 | 0 | 0.00 | 0.00 | 8.00 | 8.00 | 1 | 1.00 | 0.00 | 0.00 | 100.00 | 2026-04-07T12:52:05.705Z | 2026-04-07T12:52:05.705Z | TMS_ORACLE |
| 10 | 2025-08-18 | GBEA | CFSGDYR031 | 1 | 0 | 1 | 0 | 0 | 0.00 | 0.00 | 8.00 | 8.00 | 1 | 1.00 | 0.00 | 0.00 | 100.00 | 2026-04-07T12:52:05.705Z | 2026-04-07T12:52:05.705Z | TMS_ORACLE |

---

## Table 3: go_shipment_facts

| id | SHIPMENT_ID | TC_SHIPMENT_ID | TC_COMPANY_ID | REF_SHIPMENT_NBR | SHIPMENT_STATUS | SHIPMENT_TYPE | MOVE_TYPE | BUSINESS_PROCESS | IS_SHIPMENT_CANCELLED | IS_SHIPMENT_RECONCILED | CREATED_DTTM | LAST_UPDATED_DTTM | SHIPMENT_START_DTTM | SHIPMENT_END_DTTM | TENDER_DTTM | PICKUP_START_DATE | PICKUP_END_DTTM | DELIVERY_START_DTTM | DELIVERY_END_DTTM | O_FACILITY_ID | O_FACILITY_NUMBER | O_STOP_LOCATION_NAME | O_ADDRESS | O_CITY | O_STATE_PROV | O_POSTAL_CODE | O_COUNTRY_CODE | D_FACILITY_ID | D_FACILITY_NUMBER | D_STOP_LOCATION_NAME | D_ADDRESS | D_CITY | D_STATE_PROV | D_POSTAL_CODE | D_COUNTRY_CODE | ASSIGNED_CARRIER_CODE | ASSIGNED_CARRIER_ID | DSG_CARRIER_CODE | EQUIPMENT_TYPE | TRAILER_NUMBER | TRLR_TYPE | TRLR_SIZE | DISTANCE | DIRECT_DISTANCE | OUT_OF_ROUTE_DISTANCE | DISTANCE_UOM | NUM_STOPS | PLANNED_WEIGHT | PLANNED_VOLUME | TOTAL_COST | ACTUAL_COST | ESTIMATED_COST | LINEHAUL_COST | ACCESSORIAL_COST | CURRENCY_CODE | DAYS_TO_DELIVER | IS_HAZMAT | IS_PERISHABLE | BILL_TO_CODE | BILL_OF_LADING_NUMBER | BILL_TO_STATE_PROV | BILL_TO_POSTAL_CODE | ASSIGNED_SERVICE_LEVEL_ID | VENDOR_NAME | FISCAL_YEAR_WEEK | FISCAL_YEAR_MONTH | carrier_key | facility_key | TOTAL_REVENUE | ON_TIME_FLAG | COST_PER_MILE | load_date | update_date | source_system |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 7 | CS00009409 | CS00009409 | L1-DSG-DEV | 2014-06-009409 | 80 | Inbound | PICKUP | VENDOR_DIRECT | N | Y | 2014-06-18T08:00:00.000Z | 2014-06-20T14:00:00.000Z | 2014-06-19T06:00:00.000Z | 2014-06-20T14:00:00.000Z | 2014-06-18T07:00:00.000Z | 2014-06-19T06:00:00.000Z | 2014-06-19T14:00:00.000Z | 2014-06-19T14:00:00.000Z | 2014-06-21T08:00:00.000Z | V3877_6 | null | Brunton/Anchor3PL, Salt Lake City UT | null | Salt Lake City | UT | 84104 | US | 51 | null | Dedicated_51 | null | Columbus | OH | 43215 | US | GBEA | null | GBEA | TL | FANU223344 | HAZMAT_VAN | 48FT | 1876.00 | 1876.00 | 0.00 | mi | 2 | 12000.000 | 820.000 | 3800.00 | 3780.00 | 3720.00 | 3200.00 | 600.00 | USD | 2 | Y | N | DSG-CORP | BOL-2014-009409 | null | null | Standard | Brunton Outdoor | 201424 | 201406 | GBEA | V3877_6 | null | Y | 2.03 | 2026-04-07T12:36:55.664Z | 2026-04-07T12:36:55.664Z | TMS_ORACLE |
| 12 | CS20167138 | CS20167138 | L1-DSG-DEV | 2025-12-167138 | 80 | Inbound | PICKUP | VENDOR_DIRECT | N | Y | 2025-12-09T16:15:13.000Z | 2025-12-12T15:00:00.000Z | 2025-12-10T08:00:00.000Z | 2025-12-12T15:00:00.000Z | 2025-12-09T16:15:00.000Z | 2025-12-10T08:00:00.000Z | 2025-12-10T12:00:00.000Z | 2025-12-10T12:00:00.000Z | 2025-12-12T17:00:00.000Z | V72703_2 | null | Minelab Americas Inc, Aurora IL | null | Aurora | IL | 60502 | US | 196 | null | Store 196 | null | Romeoville | IL | 60446 | US | FDEG | null | FDEG | PAR | FANU556677 | Container | 28FT | 342.00 | 342.00 | 0.00 | mi | 1 | 520.000 | 38.000 | 19.40 | 19.40 | 19.00 | 16.00 | 3.40 | USD | 3 | N | N | DSG-CORP | BOL-2025-167138 | null | null | Ground | Minelab Americas Inc. | 202545 | 202511 | FDEG | V72703_2 | null | Y | 0.06 | 2026-04-07T12:36:55.664Z | 2026-04-07T12:36:55.664Z | TMS_ORACLE |

---

## Table 4: go_shipment_notes

| note_id | SHIPMENT_ID | note_stop_sequence | note_text | note_prefix | note_subcategory | fiscal_year_month | fiscal_year_week | load_date | update_date | source_system | note_prefix_o |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | CNKL4016376 | 2 | O-CA-Carrier Capacity | O | CA | Carrier Capacity | 202603 | +202611-01-01T00:00:00.000Z | 2026-04-07T12:40:39.784Z | 2026-04-07 12:40:39.784551 | TMS_ORACLE | (null) |
| 2 | CNKL4018375 | 3 | O-S-Store Detention | O | S | Store Detention | 202603 | +202611-01-01T00:00:00.000Z | 2026-04-07T12:40:39.784Z | 2026-04-07 12:40:39.784551 | TMS_ORACLE | (null) |
