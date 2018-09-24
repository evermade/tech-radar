# Evermade Technology Radar 2018

Welcome to Evermade tech radar - inspired by Zalando. This is intended to help our developers to improve their skills and pick up the right tools for projects. Tech radar is referring to our future plan - not necessarily the existing stack.

Tools and technologies are divided into four categories:

- **Adopt**  
  Technologies we should use and we should get familiar with.
- **Trial**  
  Widely used mature technologies we will most likely adopt to our workflow at some point.
- **Assess**  
  Something we see could be our part of our stack in the future but might still be too experimental or business needs are still unclear.
- **Hold**  
  Technologies we should avoid. We might have used these in the past but we are not going to use in the future.

## Methodologies / concepts

### Adopt

- **Analytics**  
  Analytics is more than just throwing in GTM script to the footer. Settings goals and following them should start from the first line of code we write. Better analytics understanding is one of our core company goals.
- **Continuous integration & deployment**  
  Just `git push` and magic happens. Too fun to be ignored.
- **Service design**  
  Some might wonder what is this doing on tech radar? Service design means "taking a service and making it meet the user's and customer's needs". Doesn't like something developers can ignore. We are creating services for humans. Everyone in our company should understand the meaning of the work we are doing.
- **Architecture design**  
  Serverless? MVC? Separation of concerns? Understanding software architecture design and patterns helps us to make better decisions.

### Trial

- **Automatic testing and test driven development**  
  Really helps to improve the quality and saves time in long run. Testing requires a mindset change and adaptation of new tools.
- **Scrum & project management**  
  We are aiming to more self driven direction and understanding how to run agile projects helps.
- **REST API design**  
  Almost every project involves some kind of API integration. Sometimes we use APIs and sometimes we design them. It's worth of understanding what it takes to design a good API.

### Assess

- **AI**  
  Ahhh, the hottest buzzword out there. Let's keep calm and follow the situation. In the future AI will definitely be integral part of... everything. So we can't ignore it. Let's keep our eyes open.
- **AR / VR**  
  These were peaking on a hype curve a few years ago. There are some clear use cases in some projects so let's keep our eyes on this every now and then.

### Hold

- **N/A**

## Frameworks and platforms

### Adopt

- **WordPress**  
  Our number one CMS. But forget hacking with shitty plugins and ready made templates. We take WordPress more seriously.
- **React**  
  Already widely used in our projects. Must know.
- **Redux + other libraries**  
  Redux is standard state manager these days. Although it comes with some unnecessary boilerplating worth of learning. Also other related libraries like Redux Saga, Redux Thunk, ImmutableJS and Reselect.

### Trial

- **Contentful**  
  Powerful content as a service platform. Offers tools for creating content models and adding content. Works nicely with headless tools.
- **Shopify**  
  Powerful, scalable and customizable webshop saas-platform with powerful API and integration options. Has proven it's value.

### Assess

- **Express.js**  
  If we bould Node.js backend it's recommended to use Express.js as web framework. Mature, supported and capable.
- **Headless technologies**  
  Headless tools like Gatsgy.js offers reliable and fast way to compile sites. Definitely worth of investigating.
- **Laravel**  
  The best PHP framework out there. If we do backend with PHP instead of Node.js, we use Laravel.

### Hold

- **CraftCMS**  
  Great CMS and might do some things better than WordPress but overall let's try to keep our stack aligned and focus on only few platforms. Worth of experimenting and seeing how it evolves.
- **Vue**  
  Vue is great, easy to learn and powerful library. However to keep our stack unified let's focus on React.
- **Angular**  
  Great framework but let's focus on React.
- **HubSpot**  
  From developers point of view quite far from what we would like to do.

## Infrastructure and tools

### Adopt

- **Docker**  
  Docker is integral part of our tooling and everyone should have at least basic understanding how Docker works and what's the motivation of using it.
- **NPM / Yarn**  
  For today's frontend developer this should be quite obvious.
- **Webpack**  
  Module bundler for JavaScript used in almost every project.
- **Composer**  
  PHP dependency manager.
- **Bitbucket Pipelines**  
  Continuous delivery tool used in our projects.
- **NGINX**  
  Our primary web server and almost everyone needs to open config files every now and then.
- **SSL**  
  At first glance it might be weird to see SSL on this list, but understanding how certificates work and how they can be configured is definitely beneficial for all of us.

### Trial

- **End to end testing**  
  Learning end to end testing tools like Mocha/Chai/Puppeteer or Cypress is definitely worth of learning.
- **Netlify**  
  Netlify offers powerful tools for building and hosting web services. Definitely worth of looking for.
- **Amazon AWS infrastructure**  
  Amazon AWS offers zillions of different tools. Tools like EC2, Fargate, S3, CloudFront, API Gateway, Lambda and RDS are worth of looking for.
- **Server level caches**  
  Server level caches like Redis, Varnish and FastCGI Cache offers better performance than language level caches (like WordPress cache plugins). Consider using in projects.

### Assess

- **Terraform**  
  Great tool for orchestrating AWS (and other) infrastructures.
- **Swagger**  
  Swagger is a great tool for planning, documenting and testing REST APIs. Recommended for any API project.

## Hold

- **Bower**  
  Deprecated package manager. Do not touch.
- **Flightplan**  
  Flightplan is a tool to run sequences of shell commands against remote hosts. We have been using this for deployment but it will be replaced by CI.
- **CircleCI**  
  We experimented with various CI tools and ended up using Bitbucket Pipelines. To keep our stack more consistent let's not use CircleCI anymore.
- **Apache**  
  We have switched to NGINX. Apache should be used only if there's good reason to do so.
- **Ansible**  
  Ansible is great tool for orchestrating server infrastructure and we have used it extensively. However we are using ansible mostly for provisioning servers but not keeping stack up to date. For only initializing servers it's overkill and will be replaced by init scripts.
- **Gulp**  
  Although Gulp is still widely used in our projects it's more or less replaced by Webpack in later builds. Use carefully.

## Languages, language tools & transpilers

### Adopt

- **JavaScript (>= ECMAScript 2015)**  
  Just do it.
- **PHP (>= 7.2)**  
  WordPress is powered by PHP so it's good to understand the underlying language.
- **SASS**  
  Powerful extension to CSS widely used in our projects.

### Trial

- **Node.js**  
  Server side JavaScript. Node.js is natural backend choise for us, because it's widely adopted and we have experience on it.
- **TypeScript**  
  TypeScript is is a strict syntactical superset of JavaScript which brings in static typing. Definitely worth of learning and experimenting.

### Assess

- **Shell scripting**  
  Shell scripts are swiss army knifes for all developers.

### Hold

We have had internal discussions about all of these languages and some people has experience on these. However we do not see these to be suitable for Evermade. Learning curve would be too steep and educating the whole team is not worth of it. Let's focus on JavaScript/Node.js and PHP.

- **Python**
- **Go**
- **Elixir**
