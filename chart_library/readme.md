# 📊 Библиотека эталонных визуализаций

## Heatmap

1. Heatmap (Transition Matrix) в seaborn
[📓](./notebooks/heatmap_transition_matrix.ipynb)

2. Heatmap (Revenue Transition Matrix) в seaborn
[📓](./notebooks/heatmap_revenue_transition_matrix.ipynb)   
      Особенности реализации:  
      - Создание colorbar вручную    
      - Форматирование значений colorbar в виде "0М"  
      - Явно задаем порядок следования стадий на графике  


3. Heatmap (Heatmap Revenue Change Matrix) в seaborn
[📓](./notebooks/heatmap_revenue_change_matrix.ipynb)

## Cohort Heatmap
Cohort Retention Heatmap:
[📓](./notebooks/cohort_heatmap_multiset_1.ipynb)
1. Cohort Heatmap (User Retention Heatmap)  
2. Cohort Heatmap (Revenue per Retained User)  
   - форматирование colorbar в 0.0К  
3. Cohort Heatmap (Relative RPRU Growth by Cohort)  
   - Нормализованная RPRU  
4. Cohort Heatmap (Cohort LTV Heatmap)  
   - форматирование colorbar в 0.0М  

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
[📓](./notebooks/line_chart_avg_user_retention_curve.ipynb)  
      Особенности реализации:
      - сохранение MultiIndex-структуры в Pickle или Parquet
      - построение доверительного интервала
      - построение на второй оси ax2 bar с количеством когорт по месяцам.
      - построение 'Low coverage zone' пунктиром

3. Line Chart (multiset 1):
[📓](./notebooks/line_chart_multiset_1.ipynb)      
- Average Retention with Cohort Variability:  
   - две кривые на одном графике  
   - доверительные интервалы  
   - количество когорт на второй оси  
- Month-over-Month Retention Decay  
- Absolute Retention Drop  
- Lifecycle Stabilization Point: Retention and Decay Dynamics (расчет точки стабилизации)

4. Line Chart (multiset 2)
[📓](./notebooks/line_chart_multiset_2.ipynb)
- Average Revenue Growth per Retained User
      - доверительный интервал
- Retention Decay vs Monetization Growth
      - две переменные на двух осях


## ML Metrics
1. Curves
[📓](./notebooks/ml_metrics.ipynb)  
- ROC Curve  
- Precision-Recall Curve

2. SHAP Summary Plot
[📓](./notebooks/shap_summary_plot.ipynb)  
