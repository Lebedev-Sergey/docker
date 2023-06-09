Usage:  docker compose [OPTIONS] COMMAND

Options:

      --ansi string                Control when to print ANSI control characters ("never"|"always"|"auto") (default "auto")
      
      --compatibility              Run compose in backward compatibility mode
      
      --dry-run                    Execute command in dry run mode
      
      --env-file stringArray       Specify an alternate environment file.
      
  -f, --file stringArray           Compose configuration files
  
      --parallel int               Control max parallelism, -1 for unlimited (default -1)
      
      --profile stringArray        Specify a profile to enable
      
      --project-directory string   Specify an alternate working direct (default: the path of the, first specified, Compose file)
                                   
  -p, --project-name string        Project name

COMMANDS:

  build -Build or rebuild services(Создавать или перестраивать службы)
  
  config      Parse, resolve and render compose file in canonical format(Разобрать, разрешить и отобразить файл compose в каноническом формате)
  
  cp          Copy files/folders between a service container and the local filesystem(Копирование файлов/папок между служебным контейнером и локальной файловой системой)
  
  create      Creates containers for a service.(Создает контейнеры для сервиса.)
  
  down        Stop and remove containers, networks(Останавливайте и удаляйте контейнеры, сети)
  
  events      Receive real time events from containers.(Получать события в реальном времени из контейнеров.)
  
  exec        Execute a command in a running container.(Выполните команду в запущенном контейнере.)
  
  images      List images used by the created containers (Список изображений, используемых созданными контейнерами)
  
  kill        Force stop service containers.(Принудительно остановите сервисные контейнеры.)
  
  logs        View output from containers(Просмотр выходных данных из контейнеров)
  
  ls          List running compose projects(Список запущенных проектов compose)
  
  pause       Pause services(Приостановка служб)
  
  port        Print the public port for a port binding.(Выведите общедоступный порт для привязки порта.)
  
  ps          List containers(Перечислите контейнеры)
  
  pull        Pull service images(Извлекать служебные изображения)
  
  push        Push service images(Изображения Push-сервиса)
  
  restart     Restart service containers(Перезапуск служебных контейнеров)
  
  rm          Removes stopped service containers(Удаляет остановленные служебные контейнеры)
  
  run         Run a one-off command on a service.(Запустите одноразовую команду в службе.)
  
  start       Start services(Запуск служб)
  
  stop        Stop services(Остановить службы)
  
  top         Display the running processes(Отображение запущенных процессов)
  
  unpause     Unpause services(Отмените приостановку обслуживания)
  
  up          Create and start containers(Создавайте и запускайте контейнеры)
  
  version     Show the Docker Compose version information(Показать информацию о версии Docker Compose)
