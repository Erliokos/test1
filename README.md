# test1

В объекте ```mobile_init``` хранятся данные
```javascript
mobile_init = {
    skus:       [{ id: 1, name: '', category_id: 1 }...],                       // товары
    categories: [{ id: 1, name: ''}{ id: 2, name: '', parent_id: 1 }...],       // категории
    shop_skus:  {                                                               // матрица
        [matrix_type_id typeof int]: {
            [shop_id typeof int]: [{sku_id: 1}...]
        }
    }
}
```

0. Сделать хеш-таблицы по категориям и товарам ```[{id:''}] -> {id:{}}}```
1. Отрисовать на странице дерево категорий и товаров (вывести в дереве названия товаров и категорий )
2. Отрисовать на странице дерево категорий и товаров только для категорий: 169,172
3. преобразовать shop_skus в массив объектов в виде:```[{shop_id: 1, sku_id: 0, matrix_type_id: 0},{..]```
```
дерево  отрисовать в виде
  -- 1й уровень
      -- 2й уровень 
      -- 2й уровень
          -- товар
  -- 1й уровень
      -- 2й уровень
      -- товар
```
