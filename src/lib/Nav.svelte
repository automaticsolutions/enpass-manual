<nav>
  <ul>
    <li>
      <a href="#register_box">Создать аккаунт на box.com</a>
    </li>
    <li>
      <a href="#download_enpass">Скачать Enpass</a>
    </li>
    <li>
      <a href="#open_enpass">Открыть Enpass</a>
    </li>
    <li>
      <a href="#choose_webDAV">Восстановите из WebDAV</a>
    </li>
    <li>
      <a href="#setup_webDAV">Введите данные для входа на box.com</a>
    </li>
    <li>
      <a href="#master_password">Разблокируйте ваше хранилище</a>
    </li>
    <li>
      <a href="#sync">Включите синхронизацию</a>
    </li>
    <li>
      <a href="#your_passwords">Список доступных паролей</a>
    </li>
    <li>
      <a href="#settings">Настройте под себя!</a>
    </li>
  </ul>
</nav>

<style>
  nav {
    background-color: #ffffff;
    border-radius: 4px;
    box-shadow: 0 0 3px rgba(33, 33, 33, 0.33);
    min-width: 240px;
    padding: 0.5rem;
    position: sticky;
    top: 1rem;
  }

  ul {
    counter-reset: section;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  li {
    align-items: center;
    display: flex;
    font-weight: bold;
    border-radius: 4px;
  }

  li:before {
    counter-increment: section;
    content: counter(section) '.';
    padding-left: 0.5rem;
  }

  li:hover {
    background-color: rgb(244, 245, 247);
  }

  a {
    color: rgb(84, 94, 107);
    display: block;
    flex: 1;
    font-weight: 500;
    padding: 0.5rem;
    text-decoration: none;
  }

  li:hover a {
    color: rgb(54, 60, 74);
  }
</style>
