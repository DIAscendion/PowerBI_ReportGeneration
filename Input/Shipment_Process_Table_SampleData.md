# Sample Data Reference

---

## Table 1: go_carrier_performance_monthly

| Column | Row 1 | Row 2 |
|---|---|---|
| summary_id | 7 | 9 |
| summary_month | 2026-02-01 | 2026-02-01 |
| carrier_key | SDIA | SNCY |
| total_shipments_assigned | 1 | 1 |
| completed_shipments | 0 | 0 |
| cancelled_shipments | 1 | 1 |
| completion_rate_percentage | 0.00 | 0.00 |
| cancellation_rate_percentage | 100.00 | 100.00 |
| total_distance_covered | 522.00 | 601.40 |
| average_distance_per_shipment | 522.00 | 601.40 |
| total_stops_serviced | 1 | 1 |
| average_stops_per_shipment | 1.00 | 1.00 |
| route_efficiency_score | 100.00 | 100.00 |
| on_time_performance_percentage | null | null |
| carrier_utilization_percentage | 0.00 | 0.00 |
| load_date | 2026-04-07T12:54:58.617Z | 2026-04-07T12:54:58.617Z |
| update_date | 2026-04-07T12:54:58.617Z | 2026-04-07T12:54:58.617Z |
| source_system | TMS_ORACLE | TMS_ORACLE |

---

## Table 2: go_shipment_daily_summary

| Column | Row 1 | Row 2 |
|---|---|---|
| summary_id | 7 | 10 |
| summary_date | 2025-06-09 | 2025-08-18 |
| carrier_key | GBEA | GBEA |
| facility_key | CFSGDYR031 | CFSGDYR031 |
| total_shipment_count | 1 | 1 |
| active_shipment_count | 0 | 0 |
| completed_shipment_count | 1 | 1 |
| cancelled_shipment_count | 0 | 0 |
| reconciled_shipment_count | 0 | 0 |
| cancelled_shipment_percentage | 0.00 | 0.00 |
| reconciled_shipment_percentage | 0.00 | 0.00 |
| total_route_distance_sum | 8.00 | 8.00 |
| average_route_distance | 8.00 | 8.00 |
| total_stops_sum | 1 | 1 |
| average_stops_per_shipment | 1.00 | 1.00 |
| out_of_route_distance_sum | 0.00 | 0.00 |
| out_of_route_percentage | 0.00 | 0.00 |
| route_efficiency_index | 100.00 | 100.00 |
| load_date | 2026-04-07T12:52:05.705Z | 2026-04-07T12:52:05.705Z |
| update_date | 2026-04-07T12:52:05.705Z | 2026-04-07T12:52:05.705Z |
| source_system | TMS_ORACLE | TMS_ORACLE |

---

## Table 3: go_shipment_facts

| Column | Row 1 | Row 2 |
|---|---|---|
| id | 7 | 12 |
| SHIPMENT_ID | CS00009409 | CS20167138 |
| TC_SHIPMENT_ID | CS00009409 | CS20167138 |
| TC_COMPANY_ID | L1-DSG-DEV | L1-DSG-DEV |
| REF_SHIPMENT_NBR | 2014-06-009409 | 2025-12-167138 |
| SHIPMENT_STATUS | 80 | 80 |
| SHIPMENT_TYPE | Inbound | Inbound |
| MOVE_TYPE | PICKUP | PICKUP |
| BUSINESS_PROCESS | VENDOR_DIRECT | VENDOR_DIRECT |
| IS_SHIPMENT_CANCELLED | N | N |
| IS_SHIPMENT_RECONCILED | Y | Y |
| CREATED_DTTM | 2014-06-18T08:00:00.000Z | 2025-12-09T16:15:13.000Z |
| LAST_UPDATED_DTTM | 2014-06-20T14:00:00.000Z | 2025-12-12T15:00:00.000Z |
| SHIPMENT_START_DTTM | 2014-06-19T06:00:00.000Z | 2025-12-10T08:00:00.000Z |
| SHIPMENT_END_DTTM | 2014-06-20T14:00:00.000Z | 2025-12-12T15:00:00.000Z |
| TENDER_DTTM | 2014-06-18T07:00:00.000Z | 2025-12-09T16:15:00.000Z |
| PICKUP_START_DATE | 2014-06-19T06:00:00.000Z | 2025-12-10T08:00:00.000Z |
| PICKUP_END_DTTM | 2014-06-19T14:00:00.000Z | 2025-12-10T12:00:00.000Z |
| DELIVERY_START_DTTM | 2014-06-19T14:00:00.000Z | 2025-12-10T12:00:00.000Z |
| DELIVERY_END_DTTM | 2014-06-21T08:00:00.000Z | 2025-12-12T17:00:00.000Z |
| O_FACILITY_ID | V3877_6 | V72703_2 |
| O_FACILITY_NUMBER | null | null |
| O_STOP_LOCATION_NAME | Brunton/Anchor3PL, Salt Lake City UT | Minelab Americas Inc, Aurora IL |
| O_ADDRESS | null | null |
| O_CITY | Salt Lake City | Aurora |
| O_STATE_PROV | UT | IL |
| O_POSTAL_CODE | 84104 | 60502 |
| O_COUNTRY_CODE | US | US |
| D_FACILITY_ID | 51 | 196 |
| D_FACILITY_NUMBER | null | null |
| D_STOP_LOCATION_NAME | Dedicated_51 | Store 196 |
| D_ADDRESS | null | null |
| D_CITY | Columbus | Romeoville |
| D_STATE_PROV | OH | IL |
| D_POSTAL_CODE | 43215 | 60446 |
| D_COUNTRY_CODE | US | US |
| ASSIGNED_CARRIER_CODE | GBEA | FDEG |
| ASSIGNED_CARRIER_ID | null | null |
| DSG_CARRIER_CODE | GBEA | FDEG |
| EQUIPMENT_TYPE | TL | PAR |
| TRAILER_NUMBER | FANU223344 | FANU556677 |
| TRLR_TYPE | HAZMAT_VAN | Container |
| TRLR_SIZE | 48FT | 28FT |
| DISTANCE | 1876.00 | 342.00 |
| DIRECT_DISTANCE | 1876.00 | 342.00 |
| OUT_OF_ROUTE_DISTANCE | 0.00 | 0.00 |
| DISTANCE_UOM | mi | mi |
| NUM_STOPS | 2 | 1 |
| PLANNED_WEIGHT | 12000.000 | 520.000 |
| PLANNED_VOLUME | 820.000 | 38.000 |
| TOTAL_COST | 3800.00 | 19.40 |
| ACTUAL_COST | 3780.00 | 19.40 |
| ESTIMATED_COST | 3720.00 | 19.00 |
| LINEHAUL_COST | 3200.00 | 16.00 |
| ACCESSORIAL_COST | 600.00 | 3.40 |
| CURRENCY_CODE | USD | USD |
| DAYS_TO_DELIVER | 2 | 3 |
| IS_HAZMAT | Y | N |
| IS_PERISHABLE | N | N |
| BILL_TO_CODE | DSG-CORP | DSG-CORP |
| BILL_OF_LADING_NUMBER | BOL-2014-009409 | BOL-2025-167138 |
| BILL_TO_STATE_PROV | null | null |
| BILL_TO_POSTAL_CODE | null | null |
| ASSIGNED_SERVICE_LEVEL_ID | Standard | Ground |
| VENDOR_NAME | Brunton Outdoor | Minelab Americas Inc. |
| FISCAL_YEAR_WEEK | 201424 | 202545 |
| FISCAL_YEAR_MONTH | 201406 | 202511 |
| carrier_key | GBEA | FDEG |
| facility_key | V3877_6 | V72703_2 |
| TOTAL_REVENUE | null | null |
| ON_TIME_FLAG | Y | Y |
| COST_PER_MILE | 2.03 | 0.06 |
| load_date | 2026-04-07T12:36:55.664Z | 2026-04-07T12:36:55.664Z |
| update_date | 2026-04-07T12:36:55.664Z | 2026-04-07T12:36:55.664Z |
| source_system | TMS_ORACLE | TMS_ORACLE |

---

## Table 4: go_shipment_notes

| Column | Row 1 | Row 2 |
|---|---|---|
| note_id | 1 | 2 |
| SHIPMENT_ID | CNKL4016376 | CNKL4018375 |
| note_stop_sequence | 2 | 3 |
| note_text | O-CA-Carrier Capacity | O-S-Store Detention |
| note_prefix | O | O |
| note_subcategory | CA | S |
| fiscal_year_month | 202603 | 202603 |
| fiscal_year_week | +202611-01-01T00:00:00.000Z | +202611-01-01T00:00:00.000Z |
| load_date | 2026-04-07T12:40:39.784Z | 2026-04-07T12:40:39.784Z |
| update_date | 2026-04-07 12:40:39.784551 | 2026-04-07 12:40:39.784551 |
| source_system | TMS_ORACLE | TMS_ORACLE |
| note_prefix_o | null | null |
