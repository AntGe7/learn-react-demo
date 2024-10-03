## 创建 React 项目

### 1. **通过 CRA (Create React App) 创建 TypeScript 项目**
使用 Create React App (CRA) 创建 React 项目，适用于想要快速设置 TypeScript 支持的 React 应用。

#### 步骤：
1. 打开终端并运行以下命令创建 React + TypeScript 项目：

   ```bash
   npx create-react-app react-ts-demo --template typescript
   ```

2. 进入项目目录并启动项目：

   ```bash
   cd react-ts-demo
   pnpm start  # 或者使用 npm start / yarn start
   ```

3. 项目启动后，React 开发服务器将在浏览器中打开，默认端口为 `http://localhost:3000`。

### 2. **通过 Vite 创建 TypeScript 项目**
Vite 是一个快速的构建工具，适用于更轻量级和快速的 React 应用开发。

#### 步骤：
1. 打开终端并运行以下命令通过 Vite 创建 React + TypeScript 项目：

   ```bash
   pnpm create vite react-ts-vite --template react-ts
   ```

2. 进入项目目录并安装依赖：

   ```bash
   cd react-ts-vite
   pnpm install  # 或者使用 npm install / yarn install
   ```

3. 启动开发服务器：

   ```bash
   pnpm dev  # 或者使用 npm run dev / yarn dev
   ```

4. 项目启动后，Vite 开发服务器将在浏览器中打开，默认端口为 `http://localhost:5173`。

---

这两个方法分别通过 CRA(webpack) 和 Vite 快速创建带有 TypeScript 支持的 React 项目。