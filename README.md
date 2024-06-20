<p align="center">
  <img src="https://github.com/murat-cileli/dbee/assets/6532000/8f7a7d54-0904-4296-a6bb-6836ee86a095" />
  <br>
  <strong>DBee - TUI Database Browser</strong>
</p>

DBee is a terminal-based TUI application written in Go, designed for connecting to MySQL, MariaDB, and PostgreSQL databases. It offers a terminal-based interface for browsing database contents and executing SQL queries.

## Features
- Simple, lightweight, fast!
- Single executable with no dependencies
- Supports MySQL, MariaDB, and PostgreSQL
- Keyboard-centric workflow
- Save connections (except passwords)
- List database tables and views  
- View table structures and browse data  
- Execute SQL queries  
- SQL query history **(New!)**
- Fixed columns in results table  
  
[](https://github.com/murat-cileli/dbee/assets/6532000/d9d2cd86-e505-471d-91e4-d56cf8d34725)  

## Installation
Visit [Releases](https://github.com/murat-cileli/dbee/releases) section.

#### Building From Source
```console
git clone https://github.com/murat-cileli/dbee.git
cd src
go build .
./dbee
```

## Keyboard Shortcuts

**Global**  
<kbd>ESC</kbd> : Quit application

**Connections Page -> Saved Connections Pane**  
<kbd>Alt</kbd> + <kbd>S</kbd> : Focus saved connections pane  
<kbd>1 .. Z</kbd> : Selects saved connection  
<kbd>Enter</kbd> : Apply saved connection  

**Connections Page -> Connect to Server Pane**  
<kbd>Alt</kbd> + <kbd>D</kbd> : Focus connect to server pane  
<kbd>Tab</kbd> : Focus next input field  

**Main Page -> Database Objects Pane**  
<kbd>Alt</kbd> + <kbd>W</kbd> : Focus database objects pane  
<kbd>1 .. Z</kbd> : Selects a table/view  
<kbd>Enter</kbd> : Browse top 10 table/view rows  
<kbd>Ctrl</kbd> + <kbd>Space</kbd>: View table/view structure

**Main Page -> Query Pane**  
<kbd>Alt</kbd> + <kbd>Q</kbd> : Focus query pane  
<kbd>Alt</kbd> + <kbd>Enter</kbd> : Execute SQL query  
<kbd>Alt</kbd> + <kbd>Up</kbd> : Go back in query history  
<kbd>Alt</kbd> + <kbd>Down</kbd> : Go forward in query history  
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd> : Paste  
<kbd>Ctrl</kbd> + <kbd>Z</kbd> : Undo  

**Main Page -> Results Table**  
<kbd>Alt</kbd> + <kbd>R</kbd> : Focus results table  
<kbd>Arrow Keys</kbd>, <kbd>Home/End</kbd>, <kbd>Page Up/Page Down</kbd> : Navigate table

### Notes
- Contributions are welcome.
- Follow me on [LinkedIn](https://www.linkedin.com/in/murat-cileli/)
