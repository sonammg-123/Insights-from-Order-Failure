# Insights from Failed Orders 📊

Analyzed failed taxi/delivery orders using Python and Pandas to uncover insights related to driver assignment and order cancellation patterns.

## Technologies Used
- Python
- Pandas
- NumPy
- Google Colab

## Key Concepts
- Left Join using `merge()`
- Data Cleaning
- `np.where()`
- `groupby()`
- Aggregation & Counting

## Sample Code

```python
df.groupby(
    by=['is_driver_assigned', 'order_status']
)['order_gk'].count()
