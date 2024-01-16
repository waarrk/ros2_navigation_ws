# ros2_navigation_ws

## ビルド方法

```:bash
rosdep install -y \
  --from-paths ./src \
  --ignore-src
colcon build \
  --symlink-install
```

## パス通し

```:bash
source install/setup.bash
```

## 標準の起動方法

```:bash
ros2 launch nav2_bringup tb3_simulation_launch.py headless:=False
```

## ナビゲーションのパラメタファイル
src/navigation2/nav2_bringup/params/nav2_params.yaml
