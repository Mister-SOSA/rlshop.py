# rlshop.py
A simple script which will return the current Rocket League shop items in JSON format, according to data scraped from rocket-league.com



## Demo

```py
import rlshop


print(rlshop.get_shop_items())
```

```
Output > [{'name': 'Octane: Kana', 'paint': 'Black', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/33621f7b6f1566942996.png', 'type': 'Error', 'price': '200'}, {'name': 'E-Zeke', 'paint': 'Black', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/e-zeke3/e-zeke-Black.png', 'type': 'Error', 'price': '600'}, {'name': 'Takumi', 'paint': 'Purple', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/47748e5c631600443263.png', 'type': 'Error', 'price': '400'}, {'name': 'Takumi: Whizzle', 'paint': 'Unpainted', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/70b89d4b381473421042.png', 'type': 'Error', 'price': '50'}, {'name': 'NeYoYo', 'paint': 'Pink', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/neyoyo/neyoyo-Pink.png', 'type': 'Error', 'price': '900'}, {'name': 'Takumi: Vector', 'paint': 'Unpainted', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/473dcff7b51494491971.png', 'type': 'Error', 'price': '100'}, {'name': 'Encryption', 'paint': 'Black', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/f0720ca8c91628023354.png', 'type': 'Error', 'price': '2400'}, {'name': 'Toon Sketch', 'paint': 'Unpainted', 'image_url': 'https://rocket-league.com/content/media/items/avatar/220px/3d3a14be711583967555.png', 'type': 'Error', 'price': '100'}]
```
