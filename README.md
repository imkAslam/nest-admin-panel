# nest-admin

![](https://img.shields.io/github/commit-activity/m/buqiyuan/nest-admin) ![](https://img.shields.io/github/license/buqiyuan/nest-admin) ![](https://img.shields.io/github/repo-size/buqiyuan/nest-admin) ![](https://img.shields.io/github/languages/top/buqiyuan/nest-admin)

**A simple and efficient front-end and back-end separated permission management system based on NestJs + TypeScript + TypeORM + Redis + MySql + Vue3 + Ant Design Vue. Hope this project can help you on the road to full-stack development.**

- Front-end project repository: [Link](https://github.com/buqiyuan/vue3-antdv-admin)

## Demo Links

<ul>
  <li>
    <details>
      <summary>
        <a href="https://buqiyuan.gitee.io/vue3-antdv-admin/" target="_blank">
        https://buqiyuan.gitee.io/vue3-antdv-admin/
        </a> (Inside China)
      </summary>
      Read-only, you can preview the initial effect of the project completely.
    </details>
  </li>
  <li>
    <details>
      <summary>
        <a href="https://vue3-antd-admin.vercel.app/" target="_blank">
        https://vue3-antd-admin.vercel.app/
        </a> (Outside China)
      </summary>
      <ul>
        <li>
        You can freely perform CRUD operations, so the data you see may have been modified by others and may not reflect the initial effect of the project. The data in the database will be reset at 4:30 am every day.
        </li>
        <li>Since it is a free foreign server resource, it may not be stable and may require a VPN to access.</li>
      </ul>
    </details>
  </li>
  <li>
   <a href="https://nest-api.buqiyuan.site/api-docs/" target="_blank">
      Swagger Documentation
   </a>
  </li>
</ul>

## Preparation before Project Startup

- SQL file: [/deploy/sql/init.sql](https://github.com/buqiyuan/nest-admin/tree/main/deploy/sql) for database initialization
- Project-related configurations, such as configuring MySQL and Redis connections
  - Common configuration: [.env](https://github.com/buqiyuan/nest-admin/blob/main/.env)
  - Development environment: [.env.development](https://github.com/buqiyuan/nest-admin/blob/main/.env.development)
  - Production environment: [.env.production](https://github.com/buqiyuan/nest-admin/blob/main/.env.production)

## System Requirements

- `nodejs` `16.20.2`+
- `docker` `20.x`+, with `docker compose` version `2.17.0`+
- `mysql` `8.x`+
- Use [`pnpm`](https://pnpm.io/zh/) package manager to install project dependencies

Demo environment account and password:

|   Account    |  Password  |    Role    |
| :-------: | :----: | :--------: |
| admin | a123456 | Super Admin |

> All newly created user accounts have the initial password "a123456".

Local deployment account and password:

|   Account    |  Password  |    Role    |
| :-------: | :----: | :--------: |
| admin | a123456 | Super Admin |

## Quick Start

After successful startup, access <http://localhost:7001/api-docs/>.

```bash
