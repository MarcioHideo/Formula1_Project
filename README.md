 Final project - Databases Laboratory (Bachelor of Information Systems - ICMC USP)
 
### The objective of the project is to practice the knowledge studied during the discipline with the creation of a prototype that is able to manipulate data and generate reports through a good usability interface. The project uses data related to the Formula 1 sport.


### How to run
#### Prerequisites
* PostgreSQL and PgAdmin4;
* Set the three environment variables needed by the project in a copy of the .env.sample file (name this copy ".env"):
* DATABASE_NAME = 'name_of_database_created_in_postgres'
* DATABASE_PASSWORD = 'user_password_on_database_server'
* DATABASE_USERNAME = 'postgres_user'
* Python programming language installed, as well as some package manager (pip or conda, for example);

#### Step by step
* Run the following command in the project directory: `pip install -r requirements.txt`;
* In the `Project_Formula1/CreateDatabaseAndLoad)/CreateTablesAndLoad` directory, follow the instructions in the Load.txt file and run it completely in PgAdmin4, to create the tables and insert the data contained in `CreateTablesAndLoad/data`;
* Go to the `Project_Formula1/CreateDatabaseAndLoad)/CreateUsersTableAndLoad` directory and execute the commands from the `CreateUsersTable.txt` file in PgAdmin4;
* Run all the `CreateUsersTableAndLoad.py` code.
* Run files in the `Setup` directory that contain creation of functions, tables, views or triggers in PgAdmin4.
* Go back to the main directory and run the `app.py` file.
* Open the browser to the following `URL: Localhost:5000`.

---
 最終プロジェクト　- データベース論 (情報システム学士 - ICMC USP)
 
### 作品の目的は、優れたユーザビリティインターフェイスを介してデータを操作し、レポートを生成できるプロトタイプを作成して、学問分野で学習した知識を実践することです。 このプロジェクトでは、F1スポーツに関連するデータを使用しています。


### 起動方法
#### 環境構築
* PostgreSQL と PgAdmin4;
* プロジェクトに必要な3つの環境変数を.env.sampleファイルのコピーに設定します（このコピーに「.env」という名前を付けます）:
* DATABASE_NAME = 'name_of_database_created_in_postgres'
* DATABASE_PASSWORD = 'user_password_on_database_server'
* DATABASE_USERNAME = 'postgres_user'
* インストールされているPythonプログラミング言語、およびいくつかのパッケージマネージャー（pipやcondaなど）;

#### ステップバイステップ
* プロジェクトディレクトリで次のコマンドを実行します。`pipinstall-r Requirements.txt`;
* `Project_Formula1 / CreateDatabaseAndLoad）/ CreateTablesAndLoad`ディレクトリで、Load.txtファイルの指示に従い、PgAdmin4で実行して、テーブルを作成し、 `CreateTablesAndLoad/data`に含まれるデータを挿入します。;
* `Project_Formula1 / CreateDatabaseAndLoad）/ CreateUsersTableAndLoad`ディレクトリに移動し、PgAdmin4の`CreateUsersTable.txt`ファイルからコマンドを実行します；
* すべての`CreateUsersTableAndLoad.py`コードを実行します。
* PgAdmin4での関数、テーブル、ビュー、またはトリガーの作成を含む`Setup`ディレクトリ内のファイルを実行します。
* メインディレクトリに戻り、`app.py`ファイルを実行します。
* 次のURL：`URL：Localhost：5000`をブラウザで開きます。