{
  "id": 0,
  "reportId": "00000000-0000-0000-0000-000000000000",
  "filters": "[]",
  "resourcePackages": [
    {
      "resourcePackage": {
        "name": "SharedResources",
        "type": 2,
        "items": [
          {
            "name": "CY25SU10",
            "path": "BaseThemes/CY25SU10.json",
            "type": 202
          }
        ],
        "disabled": false
      }
    }
  ],
  "sections": [
    {
      "name": "ReportSection<UNIQUE_ID_1>",
      "displayName": "<PAGE_DISPLAY_NAME>",
      "filters": "[]",
      "ordinal": 0,
      "visualContainers": [
        {
          "x": "<X_POSITION>",
          "y": "<Y_POSITION>",
          "z": "<Z_ORDER>",
          "width": "<WIDTH>",
          "height": "<HEIGHT>",
          "config": "{\"name\":\"vc_<VISUAL_UNIQUE_ID>\",\"layouts\":[{\"id\":0,\"position\":{\"x\":<X_POSITION>,\"y\":<Y_POSITION>,\"z\":<Z_ORDER>,\"width\":<WIDTH>,\"height\":<HEIGHT>,\"tabOrder\":<TAB_ORDER>}}],\"singleVisual\":{\"visualType\":\"<VISUAL_TYPE>\",\"projections\":{\"<DATA_ROLE_1>\":[{\"queryRef\":\"<TABLE_NAME>.<COLUMN_NAME>\",\"active\":true}],\"<DATA_ROLE_2>\":[{\"queryRef\":\"<AGGREGATION>(<TABLE_NAME>.<COLUMN_NAME>)\"}]},\"prototypeQuery\":{\"Version\":2,\"From\":[{\"Name\":\"<ALIAS>\",\"Entity\":\"<TABLE_NAME>\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"<ALIAS>\"}},\"Property\":\"<COLUMN_NAME>\"},\"Name\":\"<TABLE_NAME>.<COLUMN_NAME>\",\"NativeReferenceName\":\"<COLUMN_DISPLAY_NAME>\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"<ALIAS>\"}},\"Property\":\"<MEASURE_COLUMN>\"}},\"Function\":<AGG_FUNCTION_CODE>},\"Name\":\"<AGGREGATION>(<TABLE_NAME>.<MEASURE_COLUMN>)\",\"NativeReferenceName\":\"<MEASURE_DISPLAY_NAME>\"}],\"OrderBy\":[{\"Direction\":<SORT_DIRECTION>,\"Expression\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"<ALIAS>\"}},\"Property\":\"<SORT_COLUMN>\"}},\"Function\":<AGG_FUNCTION_CODE>}}}]},\"drillFilterOtherVisuals\":true,\"hasDefaultSort\":true,\"vcObjects\":{\"title\":[{\"properties\":{\"text\":{\"expr\":{\"Literal\":{\"Value\":\"'<VISUAL_TITLE>'\"}}}}}]}}}",
          "filters": "[]",
          "query": "{\"Commands\":[{\"SemanticQueryDataShapeCommand\":{\"Query\":{\"Version\":2,\"From\":[{\"Name\":\"<ALIAS>\",\"Entity\":\"<TABLE_NAME>\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"<ALIAS>\"}},\"Property\":\"<COLUMN_NAME>\"},\"Name\":\"<TABLE_NAME>.<COLUMN_NAME>\",\"NativeReferenceName\":\"<COLUMN_DISPLAY_NAME>\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"<ALIAS>\"}},\"Property\":\"<MEASURE_COLUMN>\"}},\"Function\":<AGG_FUNCTION_CODE>},\"Name\":\"<AGGREGATION>(<TABLE_NAME>.<MEASURE_COLUMN>)\",\"NativeReferenceName\":\"<MEASURE_DISPLAY_NAME>\"}],\"OrderBy\":[{\"Direction\":<SORT_DIRECTION>,\"Expression\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"<ALIAS>\"}},\"Property\":\"<SORT_COLUMN>\"}},\"Function\":<AGG_FUNCTION_CODE>}}}]},\"Binding\":{\"Primary\":{\"Groupings\":[{\"Projections\":[0,1]}]},\"DataReduction\":{\"DataVolume\":4,\"Primary\":{\"Window\":{\"Count\":1000}}},\"Version\":1},\"ExecutionMetricsKind\":1}}]}",
          "dataTransforms": "{\"projectionOrdering\":{\"<DATA_ROLE_1>\":[0],\"<DATA_ROLE_2>\":[1]},\"projectionActiveItems\":{\"<DATA_ROLE_1>\":[{\"queryRef\":\"<TABLE_NAME>.<COLUMN_NAME>\",\"suppressConcat\":false}]},\"queryMetadata\":{\"Select\":[{\"Restatement\":\"<COLUMN_DISPLAY_NAME>\",\"Name\":\"<TABLE_NAME>.<COLUMN_NAME>\",\"Type\":2048},{\"Restatement\":\"<MEASURE_DISPLAY_NAME>\",\"Name\":\"<AGGREGATION>(<TABLE_NAME>.<MEASURE_COLUMN>)\",\"Type\":1}]},\"visualElements\":[{\"DataRoles\":[{\"Name\":\"<DATA_ROLE_1>\",\"Projection\":0,\"isActive\":true},{\"Name\":\"<DATA_ROLE_2>\",\"Projection\":1,\"isActive\":false}]}],\"selects\":[{\"displayName\":\"<COLUMN_DISPLAY_NAME>\",\"queryName\":\"<TABLE_NAME>.<COLUMN_NAME>\",\"roles\":{\"<DATA_ROLE_1>\":true},\"type\":{\"category\":null,\"underlyingType\":1},\"expr\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"<TABLE_NAME>\"}},\"Property\":\"<COLUMN_NAME>\"}}},{\"displayName\":\"<MEASURE_DISPLAY_NAME>\",\"queryName\":\"<AGGREGATION>(<TABLE_NAME>.<MEASURE_COLUMN>)\",\"roles\":{\"<DATA_ROLE_2>\":true},\"sort\":2,\"sortOrder\":0,\"type\":{\"category\":null,\"underlyingType\":259},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"<TABLE_NAME>\"}},\"Property\":\"<MEASURE_COLUMN>\"}},\"Function\":<AGG_FUNCTION_CODE>}}}]}",
          "tabOrder": "<TAB_ORDER>"
        }
      ],
      "config": "{}",
      "displayOption": 1,
      "width": 1280,
      "height": 720
    }
  ],
  "config": "{\"version\":\"5.69\",\"themeCollection\":{\"baseTheme\":{\"name\":\"CY25SU10\",\"type\":2,\"version\":{\"visual\":\"2.5.0\",\"report\":\"3.1.0\",\"page\":\"2.3.0\"}}},\"activeSectionIndex\":0,\"defaultDrillFilterOtherVisuals\":true,\"linguisticSchemaSyncVersion\":2,\"settings\":{\"useNewFilterPaneExperience\":true,\"allowChangeFilterTypes\":true,\"useStylableVisualContainerHeader\":true,\"queryLimitOption\":6,\"useEnhancedTooltips\":true,\"exportDataMode\":1,\"useDefaultAggregateDisplayName\":true},\"objects\":{\"section\":[{\"properties\":{\"verticalAlignment\":{\"expr\":{\"Literal\":{\"Value\":\"'Top'\"}}}}}],\"outspacePane\":[{\"properties\":{\"expanded\":{\"expr\":{\"Literal\":{\"Value\":\"false\"}}}}}]}}",
  "layoutOptimization": 0
}


================================================================================
PLACEHOLDER REFERENCE GUIDE
================================================================================

## SECTION (PAGE) PLACEHOLDERS
--------------------------------------------------------------------------------
| Placeholder              | Description                      | Example Values      |
|--------------------------|----------------------------------|---------------------|
| <UNIQUE_ID_1>            | Unique section identifier        | 6f9f1a64, a3c18f79  |
| <PAGE_DISPLAY_NAME>      | Page name shown in tab           | Sales Overview      |
--------------------------------------------------------------------------------

## VISUAL CONTAINER PLACEHOLDERS
--------------------------------------------------------------------------------
| Placeholder              | Description                      | Example Values      |
|--------------------------|----------------------------------|---------------------|
| <VISUAL_UNIQUE_ID>       | Unique visual ID (no spaces)     | sales_by_cat_001    |
| <X_POSITION>             | Horizontal position (pixels)     | 0, 500, 1000        |
| <Y_POSITION>             | Vertical position (pixels)       | 0, 310, 620         |
| <Z_ORDER>                | Layer order (higher = on top)    | 0, 1000, 2000       |
| <WIDTH>                  | Visual width (pixels)            | 480, 980            |
| <HEIGHT>                 | Visual height (pixels)           | 300, 160            |
| <TAB_ORDER>              | Tab navigation order             | 0, 1000, 2000       |
| <VISUAL_TITLE>           | Title displayed on visual        | Sales by Category   |
--------------------------------------------------------------------------------

## VISUAL TYPE PLACEHOLDERS
--------------------------------------------------------------------------------
| <VISUAL_TYPE>            | Power BI Visual Type Name                              |
|--------------------------|--------------------------------------------------------|
| clusteredColumnChart     | Clustered Column Chart                                 |
| clusteredBarChart        | Clustered Bar Chart                                    |
| lineChart                | Line Chart                                             |
| areaChart                | Area Chart                                             |
| pieChart                 | Pie Chart                                              |
| donutChart               | Donut Chart                                            |
| azureMap                 | Azure Map (filled map)                                 |
| tableEx                  | Table                                                  |
| pivotTable               | Matrix                                                 |
| card                     | Card (single value)                                    |
| multiRowCard             | Multi-Row Card (KPI cards)                             |
| slicer                   | Slicer                                                 |
| scatterChart             | Scatter Chart                                          |
| waterfallChart           | Waterfall Chart                                        |
| treemap                  | Treemap                                                |
| gauge                    | Gauge                                                  |
| kpi                      | KPI Visual                                             |
| hundredPercentStackedColumnChart | 100% Stacked Column Chart                     |
| hundredPercentStackedBarChart    | 100% Stacked Bar Chart                        |
| lineStackedColumnComboChart      | Line and Stacked Column Combo                 |
| lineClusteredColumnComboChart    | Line and Clustered Column Combo               |
| ribbonChart              | Ribbon Chart                                           |
| funnel                   | Funnel Chart                                           |
--------------------------------------------------------------------------------

## DATA ROLE PLACEHOLDERS (by Visual Type)
--------------------------------------------------------------------------------
| Visual Type              | <DATA_ROLE_1>  | <DATA_ROLE_2>  | <DATA_ROLE_3>  |
|--------------------------|----------------|----------------|----------------|
| clusteredColumnChart     | Category       | Y              | Series         |
| clusteredBarChart        | Category       | Y              | Series         |
| lineChart                | Category       | Y              | Series         |
| pieChart                 | Category       | Y              | -              |
| donutChart               | Category       | Y              | -              |
| azureMap                 | Category       | Size           | Color          |
| tableEx                  | Values         | -              | -              |
| pivotTable               | Rows           | Columns        | Values         |
| card                     | Values         | -              | -              |
| multiRowCard             | Values         | -              | -              |
| slicer                   | Values         | -              | -              |
| scatterChart             | Category       | X              | Y, Size, Series|
--------------------------------------------------------------------------------

## TABLE & COLUMN PLACEHOLDERS
--------------------------------------------------------------------------------
| Placeholder              | Description                      | Example Values      |
|--------------------------|----------------------------------|---------------------|
| <TABLE_NAME>             | Exact table name from BIM        | Orders, Products    |
| <ALIAS>                  | Short alias for query (1 char)   | o, p, s             |
| <COLUMN_NAME>            | Exact column name from BIM       | Category, Sales     |
| <COLUMN_DISPLAY_NAME>    | Display name for column          | Category            |
| <MEASURE_COLUMN>         | Column to aggregate              | Sales, Profit       |
| <MEASURE_DISPLAY_NAME>   | Display name for measure         | Sum of Sales        |
| <SORT_COLUMN>            | Column to sort by                | Sales, Order Date   |
--------------------------------------------------------------------------------

## AGGREGATION PLACEHOLDERS
--------------------------------------------------------------------------------
| <AGGREGATION>            | <AGG_FUNCTION_CODE> | Description                  |
|--------------------------|---------------------|------------------------------|
| Sum                      | 0                   | Sum of values                |
| Avg                      | 1                   | Average of values            |
| Count                    | 2                   | Count of values              |
| Min                      | 3                   | Minimum value                |
| Max                      | 4                   | Maximum value                |
| CountDistinct            | 5                   | Distinct count               |
--------------------------------------------------------------------------------

## SORT DIRECTION PLACEHOLDERS
--------------------------------------------------------------------------------
| <SORT_DIRECTION>         | Description                                        |
|--------------------------|----------------------------------------------------|
| 1                        | Ascending (A-Z, 0-9, oldest first)                 |
| 2                        | Descending (Z-A, 9-0, newest first)                |
--------------------------------------------------------------------------------

## TYPE CODES FOR queryMetadata and selects
--------------------------------------------------------------------------------
| underlyingType Code      | Data Type                                          |
|--------------------------|----------------------------------------------------|
| 1                        | String/Text                                        |
| 259                      | Double/Decimal (numeric)                           |
| 260                      | Integer                                            |
| 2048                     | String (categorical)                               |
--------------------------------------------------------------------------------


================================================================================
COMPLETE EXAMPLE: CLUSTERED COLUMN CHART
================================================================================

{
  "x": 0,
  "y": 0,
  "z": 0,
  "width": 480,
  "height": 300,
  "config": "{\"name\":\"vc_sales_by_category_001\",\"layouts\":[{\"id\":0,\"position\":{\"x\":0,\"y\":0,\"z\":0,\"width\":480,\"height\":300,\"tabOrder\":0}}],\"singleVisual\":{\"visualType\":\"clusteredColumnChart\",\"projections\":{\"Category\":[{\"queryRef\":\"Orders.Category\",\"active\":true}],\"Y\":[{\"queryRef\":\"Sum(Orders.Sales)\"}]},\"prototypeQuery\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Category\"},\"Name\":\"Orders.Category\",\"NativeReferenceName\":\"Category\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\",\"NativeReferenceName\":\"Sum of Sales\"}],\"OrderBy\":[{\"Direction\":2,\"Expression\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0}}}]},\"drillFilterOtherVisuals\":true,\"hasDefaultSort\":true,\"vcObjects\":{\"title\":[{\"properties\":{\"text\":{\"expr\":{\"Literal\":{\"Value\":\"'Sales by Category'\"}}}}}]}}}",
  "filters": "[]",
  "query": "{\"Commands\":[{\"SemanticQueryDataShapeCommand\":{\"Query\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Category\"},\"Name\":\"Orders.Category\",\"NativeReferenceName\":\"Category\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\",\"NativeReferenceName\":\"Sum of Sales\"}],\"OrderBy\":[{\"Direction\":2,\"Expression\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0}}}]},\"Binding\":{\"Primary\":{\"Groupings\":[{\"Projections\":[0,1]}]},\"DataReduction\":{\"DataVolume\":4,\"Primary\":{\"Window\":{\"Count\":1000}}},\"Version\":1},\"ExecutionMetricsKind\":1}}]}",
  "dataTransforms": "{\"projectionOrdering\":{\"Category\":[0],\"Y\":[1]},\"projectionActiveItems\":{\"Category\":[{\"queryRef\":\"Orders.Category\",\"suppressConcat\":false}]},\"queryMetadata\":{\"Select\":[{\"Restatement\":\"Category\",\"Name\":\"Orders.Category\",\"Type\":2048},{\"Restatement\":\"Sum of Sales\",\"Name\":\"Sum(Orders.Sales)\",\"Type\":1}]},\"visualElements\":[{\"DataRoles\":[{\"Name\":\"Category\",\"Projection\":0,\"isActive\":true},{\"Name\":\"Y\",\"Projection\":1,\"isActive\":false}]}],\"selects\":[{\"displayName\":\"Category\",\"queryName\":\"Orders.Category\",\"roles\":{\"Category\":true},\"type\":{\"category\":null,\"underlyingType\":1},\"expr\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Category\"}}},{\"displayName\":\"Sum of Sales\",\"queryName\":\"Sum(Orders.Sales)\",\"roles\":{\"Y\":true},\"sort\":2,\"sortOrder\":0,\"type\":{\"category\":null,\"underlyingType\":259},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Sales\"}},\"Function\":0}}}]}",
  "tabOrder": 0
}


================================================================================
COMPLETE EXAMPLE: LINE CHART
================================================================================

{
  "x": 500,
  "y": 0,
  "z": 1000,
  "width": 480,
  "height": 300,
  "config": "{\"name\":\"vc_sales_trend_002\",\"layouts\":[{\"id\":0,\"position\":{\"x\":500,\"y\":0,\"z\":1000,\"width\":480,\"height\":300,\"tabOrder\":1000}}],\"singleVisual\":{\"visualType\":\"lineChart\",\"projections\":{\"Category\":[{\"queryRef\":\"Orders.Order Date\",\"active\":true}],\"Y\":[{\"queryRef\":\"Sum(Orders.Sales)\"}]},\"prototypeQuery\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Order Date\"},\"Name\":\"Orders.Order Date\",\"NativeReferenceName\":\"Order Date\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\",\"NativeReferenceName\":\"Sum of Sales\"}],\"OrderBy\":[{\"Direction\":1,\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Order Date\"}}}]},\"drillFilterOtherVisuals\":true,\"hasDefaultSort\":true,\"vcObjects\":{\"title\":[{\"properties\":{\"text\":{\"expr\":{\"Literal\":{\"Value\":\"'Sales Trend'\"}}}}}]}}}",
  "filters": "[]",
  "query": "{\"Commands\":[{\"SemanticQueryDataShapeCommand\":{\"Query\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Order Date\"},\"Name\":\"Orders.Order Date\",\"NativeReferenceName\":\"Order Date\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\",\"NativeReferenceName\":\"Sum of Sales\"}],\"OrderBy\":[{\"Direction\":1,\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Order Date\"}}}]},\"Binding\":{\"Primary\":{\"Groupings\":[{\"Projections\":[0,1]}]},\"DataReduction\":{\"DataVolume\":4,\"Primary\":{\"Window\":{\"Count\":1000}}},\"Version\":1},\"ExecutionMetricsKind\":1}}]}",
  "dataTransforms": "{\"projectionOrdering\":{\"Category\":[0],\"Y\":[1]},\"projectionActiveItems\":{\"Category\":[{\"queryRef\":\"Orders.Order Date\",\"suppressConcat\":false}]},\"queryMetadata\":{\"Select\":[{\"Restatement\":\"Order Date\",\"Name\":\"Orders.Order Date\",\"Type\":2048},{\"Restatement\":\"Sum of Sales\",\"Name\":\"Sum(Orders.Sales)\",\"Type\":1}]},\"visualElements\":[{\"DataRoles\":[{\"Name\":\"Category\",\"Projection\":0,\"isActive\":true},{\"Name\":\"Y\",\"Projection\":1,\"isActive\":false}]}],\"selects\":[{\"displayName\":\"Order Date\",\"queryName\":\"Orders.Order Date\",\"roles\":{\"Category\":true},\"type\":{\"category\":null,\"underlyingType\":1},\"expr\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Order Date\"}}},{\"displayName\":\"Sum of Sales\",\"queryName\":\"Sum(Orders.Sales)\",\"roles\":{\"Y\":true},\"sort\":2,\"sortOrder\":0,\"type\":{\"category\":null,\"underlyingType\":259},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Sales\"}},\"Function\":0}}}]}",
  "tabOrder": 1000
}


================================================================================
COMPLETE EXAMPLE: AZURE MAP (FILLED MAP)
================================================================================

{
  "x": 500,
  "y": 310,
  "z": 3000,
  "width": 480,
  "height": 300,
  "config": "{\"name\":\"vc_sales_map_004\",\"layouts\":[{\"id\":0,\"position\":{\"x\":500,\"y\":310,\"z\":3000,\"width\":480,\"height\":300,\"tabOrder\":3000}}],\"singleVisual\":{\"visualType\":\"azureMap\",\"projections\":{\"Category\":[{\"queryRef\":\"Orders.State\",\"active\":true}]},\"prototypeQuery\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"State\"},\"Name\":\"Orders.State\",\"NativeReferenceName\":\"State\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\"}]},\"drillFilterOtherVisuals\":true,\"objects\":{\"mapControls\":[{\"properties\":{\"defaultStyle\":{\"expr\":{\"Literal\":{\"Value\":\"'grayscale_light'\"}}},\"showStylePicker\":{\"expr\":{\"Literal\":{\"Value\":\"false\"}}},\"showNavigationControls\":{\"expr\":{\"Literal\":{\"Value\":\"false\"}}}}}],\"filledMap\":[{\"properties\":{\"show\":{\"expr\":{\"Literal\":{\"Value\":\"true\"}}}}}],\"legend\":[{\"properties\":{\"show\":{\"expr\":{\"Literal\":{\"Value\":\"false\"}}}}}]},\"vcObjects\":{\"title\":[{\"properties\":{\"text\":{\"expr\":{\"Literal\":{\"Value\":\"'Sales by State'\"}}}}}]}}}",
  "filters": "[]",
  "query": "{\"Commands\":[{\"SemanticQueryDataShapeCommand\":{\"Query\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"State\"},\"Name\":\"Orders.State\",\"NativeReferenceName\":\"State\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\"}]},\"Binding\":{\"Primary\":{\"Groupings\":[{\"Projections\":[0,1]}]},\"DataReduction\":{\"DataVolume\":6,\"Primary\":{\"Top\":{}}},\"SuppressedJoinPredicates\":[1],\"Version\":1},\"ExecutionMetricsKind\":1}}]}",
  "dataTransforms": "{\"projectionOrdering\":{\"Category\":[0]},\"projectionActiveItems\":{\"Category\":[{\"queryRef\":\"Orders.State\",\"suppressConcat\":false}]},\"queryMetadata\":{\"Select\":[{\"Restatement\":\"State\",\"Name\":\"Orders.State\",\"Type\":2048}]},\"visualElements\":[{\"DataRoles\":[{\"Name\":\"Category\",\"Projection\":0,\"isActive\":true}]}],\"selects\":[{\"displayName\":\"State\",\"queryName\":\"Orders.State\",\"roles\":{\"Category\":true},\"type\":{\"category\":null,\"underlyingType\":1},\"expr\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"State\"}}},{\"displayName\":\"Sum of Sales\",\"queryName\":\"Sum(Orders.Sales)\",\"roles\":{},\"type\":{\"category\":null,\"underlyingType\":259},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Sales\"}},\"Function\":0}}}]}",
  "tabOrder": 3000
}


================================================================================
COMPLETE EXAMPLE: MULTI-ROW CARD (KPI)
================================================================================

{
  "x": 0,
  "y": 620,
  "z": 4000,
  "width": 980,
  "height": 160,
  "config": "{\"name\":\"vc_kpis_005\",\"layouts\":[{\"id\":0,\"position\":{\"x\":0,\"y\":620,\"z\":4000,\"width\":980,\"height\":160,\"tabOrder\":4000}}],\"singleVisual\":{\"visualType\":\"multiRowCard\",\"projections\":{\"Values\":[{\"queryRef\":\"Sum(Orders.Sales)\",\"active\":true},{\"queryRef\":\"Sum(Orders.Profit)\",\"active\":true},{\"queryRef\":\"Sum(Orders.Quantity)\",\"active\":true}]},\"prototypeQuery\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\",\"NativeReferenceName\":\"Sum of Sales\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Profit\"}},\"Function\":0},\"Name\":\"Sum(Orders.Profit)\",\"NativeReferenceName\":\"Sum of Profit\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Quantity\"}},\"Function\":0},\"Name\":\"Sum(Orders.Quantity)\",\"NativeReferenceName\":\"Sum of Quantity\"}]},\"drillFilterOtherVisuals\":true,\"hasDefaultSort\":false,\"vcObjects\":{\"title\":[{\"properties\":{\"text\":{\"expr\":{\"Literal\":{\"Value\":\"'Key Metrics'\"}}}}}]}}}",
  "filters": "[]",
  "query": "{\"Commands\":[{\"SemanticQueryDataShapeCommand\":{\"Query\":{\"Version\":2,\"From\":[{\"Name\":\"o\",\"Entity\":\"Orders\",\"Type\":0}],\"Select\":[{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Sales\"}},\"Function\":0},\"Name\":\"Sum(Orders.Sales)\",\"NativeReferenceName\":\"Sum of Sales\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Profit\"}},\"Function\":0},\"Name\":\"Sum(Orders.Profit)\",\"NativeReferenceName\":\"Sum of Profit\"},{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Source\":\"o\"}},\"Property\":\"Quantity\"}},\"Function\":0},\"Name\":\"Sum(Orders.Quantity)\",\"NativeReferenceName\":\"Sum of Quantity\"}]},\"Binding\":{\"Primary\":{\"Groupings\":[{\"Projections\":[0,1,2]}]},\"DataReduction\":{\"DataVolume\":3,\"Primary\":{\"Window\":{\"Count\":100}}},\"Version\":1},\"ExecutionMetricsKind\":1}}]}",
  "dataTransforms": "{\"projectionOrdering\":{\"Values\":[0,1,2]},\"projectionActiveItems\":{\"Values\":[{\"queryRef\":\"Sum(Orders.Sales)\",\"suppressConcat\":false},{\"queryRef\":\"Sum(Orders.Profit)\",\"suppressConcat\":false},{\"queryRef\":\"Sum(Orders.Quantity)\",\"suppressConcat\":false}]},\"queryMetadata\":{\"Select\":[{\"Restatement\":\"Sum of Sales\",\"Name\":\"Sum(Orders.Sales)\",\"Type\":259},{\"Restatement\":\"Sum of Profit\",\"Name\":\"Sum(Orders.Profit)\",\"Type\":259},{\"Restatement\":\"Sum of Quantity\",\"Name\":\"Sum(Orders.Quantity)\",\"Type\":260}]},\"visualElements\":[{\"DataRoles\":[{\"Name\":\"Values\",\"Projection\":0,\"isActive\":true}]}],\"selects\":[{\"displayName\":\"Sum of Sales\",\"queryName\":\"Sum(Orders.Sales)\",\"roles\":{\"Values\":true},\"type\":{\"category\":null,\"underlyingType\":259},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Sales\"}},\"Function\":0}}},{\"displayName\":\"Sum of Profit\",\"queryName\":\"Sum(Orders.Profit)\",\"roles\":{\"Values\":true},\"type\":{\"category\":null,\"underlyingType\":259},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Profit\"}},\"Function\":0}}},{\"displayName\":\"Sum of Quantity\",\"queryName\":\"Sum(Orders.Quantity)\",\"roles\":{\"Values\":true},\"type\":{\"category\":null,\"underlyingType\":260},\"expr\":{\"Aggregation\":{\"Expression\":{\"Column\":{\"Expression\":{\"SourceRef\":{\"Entity\":\"Orders\"}},\"Property\":\"Quantity\"}},\"Function\":0}}}]}",
  "tabOrder": 4000
}
 

================================================================================
CRITICAL RULES FOR LAYOUT.JSON GENERATION
================================================================================

1. **VISUAL CONTAINER NAME**: Must be unique identifier, NOT display text
   ❌ WRONG: "name": "Sales by Category"
   ✅ CORRECT: "name": "vc_sales_by_category_001"

2. **SECTION NAME**: Must start with "ReportSection" prefix
   ❌ WRONG: "name": "6f9f1a64-5d2a-4b61-9b2b-2b4e9c7d1a10"
   ✅ CORRECT: "name": "ReportSection6f9f1a64"

3. **ENTITY REFERENCES**: Must match exact table name from BIM
   ❌ WRONG: "Entity": "Sales" (if table is named "Orders")
   ✅ CORRECT: "Entity": "Orders"

4. **PROPERTY REFERENCES**: Must match exact column name from BIM
   ❌ WRONG: "Property": "ProductCategory" (if column is "Category")
   ✅ CORRECT: "Property": "Category"

5. **THEME PATH**: Must use BaseThemes folder
   ❌ WRONG: "path": "themes/CY25SU10.json"
   ✅ CORRECT: "path": "BaseThemes/CY25SU10.json"

6. **Z-ORDER**: Increment by 1000 for each visual
   ✅ CORRECT: 0, 1000, 2000, 3000, 4000

7. **TAB ORDER**: Should match Z-ORDER
   ✅ CORRECT: tabOrder matches z value

8. **AGGREGATION CONSISTENCY**: Function code must match aggregation name
   Sum → Function: 0
   Avg → Function: 1
   Count → Function: 2
   Min → Function: 3
   Max → Function: 4
   CountDistinct → Function: 5

================================================================================
