# groups.sql
CREATE TABLE Groups(   id INTEGER PRIMARY KEY AUTOINCREMENT,   title TEXT,   faculty TEXT );  INSERT INTO Groups(title, faculty) VALUES("cs-231", "csai"), ("cs-132", "csai"), ("da-231", "da"), ("cs-21", "csai"), ("da-53", "da");  SELECT * FROM Groups;
