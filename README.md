# 👉 Generic API

<div class="MainContainer">
  <div class="Introduction">
    <p>
      Generic API is an implementation of common rules when you're making an API.<br>
      This API template is ment for HTTP requests, as well as database implementation<br>
      using Express module. In general, it's made purely with NodeJS.
    </p>
    <div class="ListHeader">
      Available Features:
    </div>
    <ol>
      <li>Configuration of projecs's environment</li>
      <li>Generation of SQL queries for database configuration</li>
      <li>Migration service</li>
      <li>Automatic model configuration</li>
      <li>Easy controller implemention</li>
    </ol>
  </div>

  <hr>

  <div class="Sections">
    <section class="Environment">
      <div class="SectionHeader">
        1. Configuration of project's environment:
      </div>
      <div class="SectionBody">
        You're able to set your environment variables by creating
        a .env file, were you're requested to inform the following 
        information:
        <ol>
          <li>
            HOST
            <div class="ItemInfo">
              Your server's host, such as:
              localhost, 127.0.0.1, etc...
            </div>
          </li>
          <li>
            PORT
            <div class="ItemInfo">
              Your server's port, such as:
              3000, 3333, etc...
            </div>
          </li>
          <li>
            DATABASE
            <div class="ItemInfo">
              Your database type, such as:
              posgresql, mysql, etc...
            </div>
          </li>
          <li>
            DB_USER
            <div class="ItemInfo">
              Your database user name.
            </div>
          </li>
          <li>
            DB_PASSWORD
            <div class="ItemInfo">
              Your target database password.
            </div>
          </li>
          <li>
            DB_BASE
            <div class="ItemInfo">
              Your target database name.
            </div>
          </li>
          <li>
            DB_HOST
            <div class="ItemInfo">
              Your database host, such as:
              5432 (PostgreSQL default), or 
              3306 (MYSQL default)
            </div>
          </li>
          <li>
            DB_PORT
            <div class="ItemInfo">
              Your database port.
            </div>
          </li>
        </ol>
      </div>
    </section>
  </div>
</div>
