# teste-reviiv-aasp

# Loja AASP WordPress com WooCommerce

Este projeto é uma loja virtual construída em WordPress utilizando o tema **Storefront** com um **tema filho personalizado** e um **plugin customizado com WP Emerge** para funcionalidades adicionais.

---

## 🛠 Requisitos

- PHP 7.4+
- Composer
- Node.js e Yarn
- Servidor local (XAMPP, MAMP, Local WP, etc)

---

## 🚀 Instalação do Projeto

### 1. Instale o WordPress

Baixe e configure o WordPress localmente.

### 2. Instale o plugin WooCommerce

Baixe e configure o WooCommerce localmente na opção **Plugins** no seu painel administrativo.

### 3. Instale e ative o tema **Storefront**
Acesse **Aparência > Temas** e instale o tema Storefront a partir do repositório oficial.

### 4. Instale e ative o tema filho **Storefront-Child**
- Coloque o tema filho dentro da pasta **wp-content/themes**
- Ative o tema filho em **Aparência > Temas**

### 5. Configure a página inicial do site como "Loja" ou "Shop"se estiver em inglês

### 6. 🛒 Cadastro de Produtos
- Vá para o menu **Produtos>Adicionar novo**
- Preencha os dados de especificação do produto e publique

### 7. 🔌 Instalação do Plugin AASP Custom Products
- Instale o plugin a partir do arquivo **aasp-custom-products.zip** pelo painel administrativo em **Plugins>Adicionar Plugin**
- Acesse o terminal e entre na pasta do plugin

cd wp-content/plugins/aasp-custom-products
composer install
yarn install
yarn build

- Ative o plugin em **Plugins>Pluginsinstalados**

#### ✅ Estrutura Utilizada
Tema pai: Storefront (WooCommerce)

Tema filho personalizado: com CSS/JS customizados

Plugin customizado: WP Emerge + Blade templates

WooCommerce: Ativado para gerenciamento da loja

##### 📁 Organização

```
wp-content/
├── themes/
│   ├── storefront/           # Tema pai
│   └── storefront-child/     # Tema filho personalizado
├── plugins/
│   └── aasp-custom-products/ # Plugin customizado com WP Emerge
```
