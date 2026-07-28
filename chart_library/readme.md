# 📊 Библиотека эталонных визуализаций

## Heatmap

1. Heatmap (Transition Matrix) в seaborn
[📓](./notebooks/heatmap_transition_matrix.ipynb)

2. Heatmap (Revenue Transition Matrix) в seaborn
[📓](./notebooks/heatmap_revenue_transition_matrix.ipynb)   
      Особенности:  
      - Создание colorbar вручную    
      - Форматирование значений colorbar в виде "0М"  
      - Явно задаем порядок следования стадий на графике  


4. Heatmap (Heatmap Revenue Change Matrix) в seaborn
[📓](./notebooks/heatmap_revenue_change_matrix.ipynb)

## Sankey Diagram
1. Sankey Diagram (Customer Lifecycle Transition Flow)
[📓](./notebooks/sankey_diagram_customer_lifecycle_transition_flow.ipynb)

## Diverging Bar Chart
1. Diverging Bar Chart (Revenue Growth and Loss Drivers)
[📓](./notebooks/diverging_bar_chart_revenue_drivers.ipynb)

2. Diverging Bar Chart (Revenue Driver Classification)
[📓](./notebooks/diverging_bar_chart_revenue_driver_classification.ipynb)

## Waterfall
1. Waterfall (Revenue Decomposition)
[📓](./notebooks/waterfall_revenue_decomposition.ipynb)

## Stacked Bar Chart
1. Stacked Bar Chart (Expansion vs Contraction Revenue)
[📓](./notebooks/stacked_bar_expansion_contraction_revenue.ipynb)

## Line Chart
1. Line Chart (User Retention Curves)
[📓](./notebooks/line_chart_user_retention_curves.ipynb)

2. Line Chart (Average User Retention Curve)
Особенности реализации:
- сохранение MultiIndex-структуры в Pickle или Parquet
- построение доверительного интервала
- построение на второй оси ax2 bar с количеством когорт по месяцам.
- построение 'Low coverage zone' пунктиром
[📓](./notebooks/line_chart_avg_user_retention_curve.ipynb)
