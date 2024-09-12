<h1>Laravel Project - README</h1>
    <p>Welcome to the Laravel project. This project is built using the Laravel framework and incorporates GraphQL integration using the following packages:</p>
    <ul>
        <li><strong><code>mll-lab/laravel-graphiql</code></strong> - Version: <code>^3.2</code></li>
        <li><strong><code>nuwave/lighthouse</code></strong> - Version: <code>^6.42</code></li>
    </ul>
    <h2>Project Setup</h2>
    <p>To get started with this project, follow the steps below:</p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/your-repo/laravel-project.git</code></pre>
        <li>Navigate into the project directory:</li>
        <pre><code>cd laravel-project</code></pre>
        <li>Install dependencies:</li>
        <pre><code>composer install</code></pre>
        <li>Create a copy of the <code>.env</code> file:</li>
        <pre><code>cp .env.example .env</code></pre>
        <li>Generate an application key:</li>
        <pre><code>php artisan key:generate</code></pre>
        <li>Set up the database by editing the <code>.env</code> file with your database credentials, then run migrations:</li>
        <pre><code>php artisan migrate</code></pre>
        <li>Start the development server:</li>
        <pre><code>php artisan serve</code></pre>
        <li>Access the application at <a href="http://localhost:8000">http://localhost:8000</a></li>
    </ol>
    <h2>GraphQL Setup</h2>
    <p>This project uses GraphQL to interact with the API. The following packages were used to implement GraphQL:</p>
    <ul>
        <li><a href="https://github.com/mll-lab/laravel-graphiql">mll-lab/laravel-graphiql</a> - A simple GraphiQL interface to test GraphQL queries.</li>
        <li><a href="https://lighthouse-php.com/">nuwave/lighthouse</a> - A framework for building GraphQL APIs in Laravel.</li>
    </ul>
    <h3>Using GraphiQL</h3>
    <p>Once the project is running, you can access the GraphiQL interface at:</p>
    <pre><code>http://localhost:8000/graphiql</code></pre>
    <h3>Writing GraphQL Queries</h3>
    <p>To interact with the API using GraphQL, you can write queries in the GraphiQL interface. Here is a simple example:</p>
    <pre><code>
    query {
        user(id: 1) {
            id
            name
            email
        }
    }
    </code></pre>
    <h2>Additional Information</h2>
    <p>For more details on using Laravel, GraphiQL, or Lighthouse, refer to the official documentation:</p>
    <ul>
        <li><a href="https://laravel.com/docs">Laravel Documentation</a></li>
        <li><a href="https://lighthouse-php.com/">Lighthouse Documentation</a></li>
        <li><a href="https://github.com/mll-lab/laravel-graphiql">Laravel GraphiQL Documentation</a></li>
    </ul>

