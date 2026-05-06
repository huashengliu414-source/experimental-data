# 实验数据仓库

**上传时间**: 2026-05-06 13:58:40

## 数据概况

| 类别 | 数量 | 状态 |
|------|------|------|
| 小文件 (<25MB) | 304 个 | ✅ 可通过API上传 |
| 中等文件 (25-100MB) | 25 个 | ⚠️ 需要分批上传 |
| 超大文件 (>100MB) | 69 个 | ❌ 需要Git LFS |
| **总计** | 398 个 | - |

## 数据内容

### 1. 三个指数 (2014-2024)
- **DEVI**: 增强型植被指数
- **LSWI**: 陆地表面水指数  
- **NDVI**: 归一化植被指数

### 2. 时序分析
- 各年份栅格数据 (.tif)
- 变化速率分析
- 一元线性回归结果

### 3. 驱动机制
- 地形因子 (高程、坡度、坡向)
- 气候因子 (气温、降水)
- 人文因子 (GDP、人口密度)
- 分析结果和图表

## 超大文件清单

以下 69 个文件超过100MB，需要安装Git和Git LFS后手动上传：

| 文件路径 | 大小 |
|---------|------|
| `三个指数/2015/DEVI/2015-DEVI-1.dat` | 440.8 MB |
| `三个指数/2015/LSWI/2015-LWSI-1.dat` | 440.8 MB |
| `三个指数/2015/NDVI/2015-NDVI-2.dat` | 440.8 MB |
| `三个指数/2018/DEVI/2018-DEVI-1.dat` | 438.8 MB |
| `三个指数/2018/LSWI/2018-LWSI-1.dat` | 438.8 MB |
| `三个指数/2018/NDVI/2018-NDVI-2.dat` | 438.8 MB |
| `三个指数/2019/DEVI/2019-DEVI-1.dat` | 438.8 MB |
| `三个指数/2019/LSWI/2019-LSWI-2.dat` | 438.8 MB |
| `三个指数/2019/NDVI/2019-NDVI-2.dat` | 438.8 MB |
| `三个指数/2020/DEVI/2020-DEVI-1.dat` | 438.8 MB |
| `三个指数/2020/LSWI/2020-LSWI-2.dat` | 438.8 MB |
| `三个指数/2020/NDVI/2020-NDVI-2.dat` | 438.8 MB |
| `三个指数/2023/DEVI/2023-DEVI-1.dat` | 438.5 MB |
| `三个指数/2023/LSWI/2023-LSWI-2.dat` | 438.5 MB |
| `三个指数/2023/NDVI/2023-NDVI-2.dat` | 438.5 MB |
| `三个指数/2014/DEVI/2014-DEVI-1.dat` | 438.3 MB |
| `三个指数/2014/LSWI/2014-LWSI-1.dat` | 438.3 MB |
| `三个指数/2014/NDVI/2014-NDVI-1.dat` | 438.3 MB |
| `三个指数/2016/DEVI/2016-DEVI-1.dat` | 438.3 MB |
| `三个指数/2016/LSWI/2016-LSWI-2.dat` | 438.3 MB |
| `三个指数/2016/ndvi/2016-ndvi-2.dat` | 438.3 MB |
| `三个指数/2017/DEVI/2017-DEVI-1.dat` | 438.3 MB |
| `三个指数/2017/LSWI/2017-LSWI-2.dat` | 438.3 MB |
| `三个指数/2017/NDVI/2017-NDVI-2.dat` | 438.3 MB |
| `三个指数/2022/DEVI/2022-DEVI.dat` | 438.3 MB |
| `三个指数/2022/LSWI/2022-LSWI-2.dat` | 438.3 MB |
| `三个指数/2022/NDVI/2022-ndvi-2.dat` | 438.3 MB |
| `三个指数/2024/DEVI/2024-DEVI-1.dat` | 434.0 MB |
| `三个指数/2024/LSWI/2024-LSWI-2.dat` | 434.0 MB |
| `三个指数/2024/NDVI/NDVI-2024-2.dat` | 434.0 MB |
| `三个指数/2021/DEVI/2021-DEVI-1.dat` | 433.8 MB |
| `三个指数/2021/LSWI/2021-LWSI-2.dat` | 433.8 MB |
| `三个指数/2021/NDVI/2021-NDVI-2.dat` | 433.8 MB |
| `三个指数/2015/DEVI/2015-DEVI-1.dat.enp` | 146.9 MB |
| `三个指数/2015/NDVI/2015-NDVI-2.dat.enp` | 146.9 MB |
| `三个指数/2015/LSWI/2015-LWSI-1.dat.enp` | 146.9 MB |
| `三个指数/2020/DEVI/2020-DEVI-1.dat.enp` | 146.2 MB |
| `三个指数/2018/LSWI/2018-LWSI-1.dat.enp` | 146.2 MB |
| `三个指数/2020/NDVI/2020-NDVI-2.dat.enp` | 146.2 MB |
| `三个指数/2019/DEVI/2019-DEVI-1.dat.enp` | 146.2 MB |
| `三个指数/2018/NDVI/2018-NDVI-2.dat.enp` | 146.2 MB |
| `三个指数/2019/NDVI/2019-NDVI-2.dat.enp` | 146.2 MB |
| `三个指数/2020/LSWI/2020-LSWI-2.dat.enp` | 146.2 MB |
| `三个指数/2019/LSWI/2019-LSWI-2.dat.enp` | 146.2 MB |
| `三个指数/2018/DEVI/2018-DEVI-1.dat.enp` | 146.2 MB |
| `三个指数/2023/DEVI/2023-DEVI-1.dat.enp` | 146.1 MB |
| `三个指数/2023/NDVI/2023-NDVI-2.dat.enp` | 146.1 MB |
| `三个指数/2023/LSWI/2023-LSWI-2.dat.enp` | 146.1 MB |
| `三个指数/2014/DEVI/2014-DEVI-1.dat.enp` | 146.0 MB |
| `三个指数/2017/LSWI/2017-LSWI-2.dat.enp` | 146.0 MB |
| `三个指数/2016/ndvi/2016-ndvi-2.dat.enp` | 146.0 MB |
| `三个指数/2017/DEVI/2017-DEVI-1.dat.enp` | 146.0 MB |
| `三个指数/2014/NDVI/2014-NDVI-1.dat.enp` | 146.0 MB |
| `三个指数/2014/LSWI/2014-LWSI-1.dat.enp` | 146.0 MB |
| `三个指数/2016/LSWI/2016-LSWI-2.dat.enp` | 146.0 MB |
| `三个指数/2016/DEVI/2016-DEVI-1.dat.enp` | 146.0 MB |
| `三个指数/2022/DEVI/2022-DEVI.dat.enp` | 146.0 MB |
| `三个指数/2017/NDVI/2017-NDVI-2.dat.enp` | 146.0 MB |
| `三个指数/2022/LSWI/2022-LSWI-2.dat.enp` | 146.0 MB |
| `三个指数/2022/NDVI/2022-ndvi-2.dat.enp` | 146.0 MB |
| `三个指数/2024/NDVI/NDVI-2024-2.dat.enp` | 144.6 MB |
| `三个指数/2024/DEVI/2024-DEVI-1.dat.enp` | 144.6 MB |
| `三个指数/2024/LSWI/2024-LSWI-2.dat.enp` | 144.6 MB |
| `三个指数/2021/LSWI/2021-LWSI-2.dat.enp` | 144.5 MB |
| `三个指数/2021/NDVI/2021-NDVI-2.dat.enp` | 144.5 MB |
| `三个指数/2021/DEVI/2021-DEVI-1.dat.enp` | 144.5 MB |
| `驱动机制/4261结果/全部数据/DEVI.tif` | 109.4 MB |
| `驱动机制/4261结果/全部数据/LSWI.tif` | 109.4 MB |
| `驱动机制/4261结果/全部数据/NDVI.tif` | 109.4 MB |

## 如何完整上传

由于当前环境缺少Git，以下文件尚未上传。请按以下步骤完成上传：

### 方法1: 安装Git后使用脚本
1. 下载并安装 Git for Windows: https://git-scm.com/download/win
2. 下载并安装 Git LFS: https://git-lfs.github.com/
3. 运行完整上传脚本

### 方法2: 手动上传
1. 在本地安装Git
2. 克隆仓库: `git clone https://github.com/huashengliu414-source/experimental-data.git`
3. 复制数据文件到仓库目录
4. 配置LFS: `git lfs track "*.dat"` 等
5. 提交并推送

## 当前已上传文件

此仓库目前包含:
- ✅ README.md (本文件)
- ✅ 超大文件清单 (LARGE_FILES.md)
- ⚠️ 其他文件待上传

---
*自动生成于 {datetime.now().strftime('%Y-%m-%d')}*
