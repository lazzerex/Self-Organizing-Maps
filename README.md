# Nhóm 2 - Self-Organizing Maps

Demo cho bài toán phân cụm khách hàng trên bộ dữ liệu Credit Card Dataset (Data/CC GENERAL.csv) bằng Self-Organizing Maps.

## Nội dung chính

- Khảo sát dữ liệu và xử lý giá trị thiếu
- Chuẩn hóa dữ liệu bằng MinMaxScaler
- Cài đặt Self-Organizing Maps
- Trực quan hóa bằng U-Matrix, hit map, PCA 2D, silhouette
- So sánh với KMeans và DBSCAN
- Lưu và nạp mô hình

## File chính

- `som.ipynb`: file jypyter notebook Self-Organizing Maps
- `Data/CC GENERAL.csv`: dữ liệu đầu vào
- `Output/SOM_CC_GENERAL.mdl`: mô hình đã lưu
- `Output/som_u_matrix.png`: U-Matrix của Self-Organizing Maps
- `Output/som_hit_map.png`: hit map của Self-Organizing Maps
- `Output/som_elbow.png`: biểu đồ ELBOW trên trọng số Self-Organizing Maps
- `Output/som_silhouette_scan.png`: silhouette theo số cụm của Self-Organizing Maps
- `Output/som_pca_2d.png`: PCA 2D của Self-Organizing Maps
- `Output/som_silhouette_detail.png`: silhouette detail của Self-Organizing Maps
- `Output/som_bmu_map.png`: bản đồ BMU của Self-Organizing Maps
- `Output/som_cluster_profile.csv`: bảng trung bình theo cluster của Self-Organizing Maps
- `Output/som_cluster_labels.csv`: dữ liệu đã gán nhãn cluster của Self-Organizing Maps
- `Output/kmeans_metrics.csv`: kết quả của KMeans
- `Output/dbscan_metrics.csv`: kết quả của DBSCAN
- `Output/clustering_summary.csv`: bảng tổng hợp so sánh 3 thuật toán
