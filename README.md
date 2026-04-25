@Entity – класс данных, представляющий таблицу в БД
Каждое поле → столбец

@PrimaryKey(autoGenerate = true) для автоматической генерации ID

@Dao – интерфейс с методами доступа к данным

@Insert, @Update, @Delete – простые операции

@Query("SQL запрос") – сложные запросы
Для наблюдения за данными используйте Flow<T> (обновляется автоматически)

@Database – абстрактный класс RoomDatabase
Указывает entities и version
Синглтон через companion object
