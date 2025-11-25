## Changes

### 3.1
#### 3.1.0
- Removed unnecessary dependencies including Hadoop, Parquet, Gson, Jackson, and other related libraries.
- Retained only the core runtime dependencies.
- Skipped shading/renaming for several HDFS-related JARs since HDFS has already been upgraded and is now fully compatible with the new version.

### 3.0
#### 3.0.0
- Upgrade paimon to 1.1.1
- Upgrade iceberg to 1.9.1
#### 3.0.1
- Upgrade avro to 1.12 to match iceberg 1.9.1 

### 2.1
#### 2.1.0
- Upgrade paimon to 0.8.0
- Upgrade bcpkix-jdkon15 dependency to bcpkix-jdkon18
#### 2.1.1
- Upgrade paimon to 0.8.1
#### 2.1.2
- Upgrade paimon to 0.9.0
#### 2.1.3
- Upgrade paimon to 1.0.0
- Upgrade iceberg to 1.6.1
#### 2.1.4
- Upgrade paimon to 1.0.1
### 2.0
#### 2.0.0
- upgrade avro to 1.11.3
- upgrade parquet to 1.13.1
- upgrade guava to 32.1.2-jre
- upgrade gson to 2.10
- upgrade bcprov to 1.70
- upgrade paimon to 0.7.0
- exclude some dependencies

#### 2.0.1
- Set HikariCP Scope to Provided (#42)

#### 2.0.2
- The com.aliyun.datalake package should not be renamed
