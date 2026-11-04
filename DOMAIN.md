# AI Dev Platform

The platform connects employees, projects, agents, and company rules for AI-first development.
(Платформа связывает сотрудников, проекты, агентов и правила компании для AI-first разработки.)

## Language (Термины)

**Employee (Сотрудник)**:
A person in the company who holds a platform account and can receive access to projects.
(Человек компании, которому принадлежит учётная запись платформы и который может получать доступ к проектам.)
_Avoid_: user — when referring specifically to an employee.
(_Избегать_: пользователь — когда речь идёт именно о сотруднике.)

**Administrator (Администратор)**:
An employee whose role allows them to manage invitations, projects, integrations, and access assignments.
(Сотрудник с ролью управления приглашениями, проектами, интеграциями и назначениями доступа.)
This role alone does not grant access to project content.
(Эта роль сама по себе не означает доступ к содержимому проектов.)
_Avoid_: project owner — as a synonym for administrator.
(_Избегать_: владелец проекта — как синоним администратора.)

**Project (Проект)**:
A collection of repositories and instructions that employees receive access to as a whole.
(Совокупность репозиториев и инструкций, к которой сотрудники получают доступ как к единому целому.)
_Avoid_: service, repository — as synonyms for project.
(_Избегать_: сервис, репозиторий — как синонимы проекта.)

**Project member (Участник проекта)**:
An employee assigned access to a project.
(Сотрудник, которому назначен доступ к проекту.)
_Avoid_: team member — teams and projects are distinct concepts.
(_Избегать_: член команды — команды не тождественны проектам.)

**Project repository (Репозиторий проекта)**:
A source code repository included in a project; one repository can belong to several projects.
(Репозиторий исходного кода, включённый в состав проекта; один репозиторий может входить в несколько проектов.)
_Avoid_: project — as a synonym for repository.
(_Избегать_: проект — как синоним репозитория.)

**Project instructions (Инструкции проекта)**:
Information for working on a project, including environment requirements, setup steps, and a readiness check.
(Сведения для работы с проектом, включая требования к окружению, шаги подготовки и способ проверки готовности.)
_Avoid_: skill — as a synonym for the full set of project instructions.
(_Избегать_: скилл — как синоним всех инструкций проекта.)

**Developer agent (Агент разработчика)**:
An agent that an employee connects to the platform to work within that employee's permissions.
(Агент, которого сотрудник подключает к платформе для работы в пределах собственных прав.)
_Avoid_: company agent — this is a separate direction for future development.
(_Избегать_: агент компании — это отдельное направление развития.)

**Access assignment (Назначение доступа)**:
Permission for an employee to work on a project, including its instructions and all its repositories.
(Разрешение сотруднику работать с проектом, включая его инструкции и все репозитории.)
_Avoid_: role — a role and a project access assignment are distinct concepts.
(_Избегать_: роль — роль и назначение доступа к проекту различаются.)

**Effective access (Фактический доступ)**:
An employee's ability to retrieve data or modify repositories, considering all active sources of access.
(Возможность сотрудника получать данные или изменять репозитории с учётом всех действующих оснований доступа.)
_Avoid_: access assignment — an assignment does not guarantee successful provisioning or complete revocation of permissions.
(_Избегать_: назначение доступа — назначение не гарантирует успешную выдачу или полный отзыв прав.)

**External assignment (Внешнее назначение)**:
A source of repository access established outside the platform, such as membership in a GitHub team.
(Основание доступа к репозиторию, созданное вне платформы, например участие в команде GitHub.)
_Avoid_: platform access — when the platform did not create the assignment.
(_Избегать_: доступ платформы — когда платформа не создавала это назначение.)

**Project onboarding (Подключение к проекту)**:
The process of obtaining access and preparing a working environment, completed by a successful check specified in the project instructions.
(Процесс получения доступа и подготовки рабочего окружения, завершённый успешной проверкой по инструкциям проекта.)
_Avoid_: downloading repositories — as a name for the entire process.
(_Избегать_: скачивание репозиториев — как обозначение всего процесса.)

**Access revocation (Отзыв доступа)**:
The process of ending access within a defined scope, completed by verifying the absence of effective access.
(Процесс прекращения доступа в заданной области, завершённый проверкой отсутствия фактического доступа.)
_Avoid_: account deletion — as a synonym for access revocation.
(_Избегать_: удаление учётной записи — как синоним отзыва доступа.)
