<p align="center">
  <a href="https://angular-ru.github.io" target="_blank">
    <img src="/media/awesome-angular.png" alt="Awesome Angular" />
  </a>
</p>

# Awesome Angular [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/gdi2290/awesome-angular)

Здесь вы найдете список полезных репозиториев, стартеры, примеры, учебные пособия, компоненты, модули, видеоролики и все остальное причастное к экосистеме Angular.

 [![Angular-RU](https://img.shields.io/badge/Telegram_chat:-Angular_RU-216bc1.svg?style=flat)](https://t.me/angular_ru)

##### Current Angular version:
[![npm version](https://badge.fury.io/js/%40angular%2Fcore.svg)](https://www.npmjs.com/~angular)

##### Current Browser support for Angular:
[![Sauce Test Status](https://saucelabs.com/browser-matrix/angular2-ci.svg)](https://saucelabs.com/u/angular2-ci)

**Содержание**:

* [Angular](#angular)
  * [Официальные ресурсы](#angular-official)
  * [Новости в twitter](#twitter)
  * [Сообщества](#community)
  * [Серверный рендеринг](#server-side-rendering)
  * [Cheatsheet (чит-лист)](#cheatsheet)
  * [UI библиотеки](#angular-ui)
    * [Material Design](#material)
  * [Важные особенности](#features)
    * [Компоненты](#components)
    * [Шаблоны](#templates)
    * [Обнаружение изменений](#change-detection)
    * [Внедрение зависимостей](#dependency-injection)
    * [Директивы](#directives)
    * [Пайпы](#pipes)
    * [Web Workers](#web-workers)
    * [HTTP](#http)
    * [Роутинг](#router)
    * [Тестирование](#test)
    * [Ahead-of-Time компиляция](#aot)
  * [Angular CLI](#angular-cli)
  * [Webpack стартеры](#webpack)
  * [Публикации](#series)
  * [Видеоуроки](#video-tutorials)
  * [Стайл-гайды](#style-guides)
  * [Angular Connect конференция](#angular-connect)
  * [Книги](#books)
  * [Курсы и тренинги](#on-site-training)
  * [Различные подходы](#approach-and-explanation)
  * [Интеграция](#integrations)
  * [Компоненты](#components)
  * [Примеры приложений](#site-templates)
  * [Генераторы](#generators)
  * [Инструменты документации](#documentation-tools)
  * [TodoMVC](#todomvc)
    
--------

<h2 id="angular">Angular</h2>

> Angular - это платформа для разработки мобильных и десктопных веб-приложений.

<h3 id="angular">Официальные ресурсы</h3>

* [Сайт](https://angular.io/)
* [Блог](http://angularjs.blogspot.com/)
* [Документация по фреймворку](https://angular.io/docs/js/latest/)
* [Чит-лист частовстречающихся вещей в Angular](https://angular.io/guide/cheatsheet)
* [Быстрый старт](https://angular.io/guide/quickstart)
* [GitHub репозиторий](https://github.com/angular/angular)

<h3 id="twitter">Новости в twitter</h3>

> Данный список хорош тем, что благодаря нему, вы будете в курсе основных событий.

##### Angular Team (эксперты из команды Angular)

* [Мишко Хевери (@mhevery)](https://twitter.com/mhevery)
* [Игор Минар (@mhevery)](https://twitter.com/mhevery)
* [Брэд Грин (bradlygreen)](https://twitter.com/bradlygreen)
* [Наоми Блэк (@naomitraveller)](https://twitter.com/naomitraveller)
* [Тобиас Бош (@tbosch1009)](https://twitter.com/tbosch1009)
* [Кара Эриксон (@karaforthewin)](https://twitter.com/karaforthewin)
* [Роб Уормальд (@robwormald)](https://twitter.com/robwormald)

##### [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)
* [Джек Франклин](https://twitter.com/jack_franklin)
* [Тьерри Шатель](https://twitter.com/ThierryChatel)
* [Ури Шейк](https://twitter.com/urishaked)
* [Гонсало Руис из Виллы Суарес](https://twitter.com/gruizdevilla)
* [Джон Папа](https://twitter.com/sharondio)
* [Джон Папа](https://twitter.com/John_Papa)
* [Дэн Вахлин](https://twitter.com/danwahlin)
* [Кристиан Вейер](https://twitter.com/christianweyer)
* [Тоддский девиз](https://twitter.com/toddmotto)
* [Тим Раффлес](https://twitter.com/timruffles)
* [Вассим Чхаг](https://twitter.com/manekinekko)
* [Aaron Frost](https://twitter.com/js_dev)
* [Аарон Фрост](https://twitter.com/willmendesneto)
* [Джаред Уильямс](https://twitter.com/jaredwilli)
* [Жерар Санс](https://twitter.com/gerardsans)
* [Паскаль Прехт](https://twitter.com/PascalPrecht)
* [Джефф Whelpley](https://twitter.com/jeffwhelpley/)
* [Рауль Хименес](https://twitter.com/elecash/)
* [Киро Нанес](https://twitter.com/cironunesdev/)
* [Максим Сальников](https://twitter.com/webmaxru)
* [Дебора Курата](https://twitter.com/deborahkurata)
* [Минько Гечев](https://twitter.com/mgechev)
* [Шай Резник](https://twitter.com/shai_reznik)

##### Остальные известные эксперты:

* [Патрик Стэплтон (@gdi2290)](https://twitter.com/gdi2290)
* [Скотт Мосс (@scotups)](https://twitter.com/scotups)
* [Брэд Грин (@bradlygreen)](https://twitter.com/bradlygreen)
* [Джефф Кросс (@jeffbcross)](https://twitter.com/jeffbcross)
* [Виктор Савкин (@victorsavkin)](https://twitter.com/victorsavkin)
* [Павел Козловский (@pkozlowski_os)](https://twitter.com/pkozlowski_os)
* [Алексей Охрименко (@Ai_boy)](https://twitter.com/Ai_boy)

##### Сообщества:

* [egghead.io (@eggheadio)](https://twitter.com/eggheadio)
* [hirez.io (@hirez_io)](https://twitter.com/hirez_io)
* [hypedrivendev.io (@cedric_exbrayat)](https://twitter.com/cedric_exbrayat)
* [amcdnl.com (@amcdnl)](https://twitter.com/amcdnl)

##### Митапы:

* [Angular Moscow (@AngularMoscow)](https://twitter.com/AngularMoscow)
* [Angular NYC (@ngNewYork)](https://twitter.com/ngNewYork)

Этот список далеко не полный...

<h3 id="community">Сообщества</h3>

* [`Angular сообщества в twitter`](https://twitter.com/search?f=users&vertical=default&q=%23angular&src=tyah)

![](https://habrastorage.org/webt/uo/hi/ce/uohices8pudw2cib-lji_yp4wte.png)

* [Канал в Gitter](https://gitter.im/angular/angular)
* [Вопросы по Angular на StackOverflow](https://stackoverflow.com/questions/tagged/angular)
* [Angular на Reddit](https://www.reddit.com/r/Angular2/)
* [Подкасты от AngularAir](http://angularair.com/)
* [Подкатсы от Devchat по Angular](https://devchat.tv/adv-in-angular)
* [Журнал ng-newsletter](http://www.ng-newsletter.com)
* [Витрина приложений от Angular Expo](http://angularexpo.com/)
* [Чат от AngularBuddies в Slack](https://angularbuddies.slack.com/messages/ng-2/)
* [Чат от dartlang.slack.com в Slack](https://dartlang.slack.com/messages/angular2) 
* [Подборка популярных Twitter's аккаунтов](http://theherdlocker.com/tweet/popularity/angular2)

<h3 id="server-side-rendering">Серверный рендеринг</h3>

* [Официальный репозиторий Angular Universal (GitHub)](https://github.com/angular/universal)
* [Русскоязычный репозиторий Angular Universal (GitHub)](https://github.com/Angular-RU/angular-universal-starter)

<h3 id="cheatsheet">Cheatsheet (чит-лист)</h3>

* [Официальный cheatsheet от Angular](https://angular.io/guide/cheatsheet)
* [Официальный cheatsheet по AngularDart](https://docs.google.com/document/d/1FYyA-b9rc2UtlYyQXjW7lx4Y08MSpuWcbbuqVCxHga0/edit#heading=h.34sus6g4zss3)
* [Еще один cheatsheet для AngularDart](https://github.com/andresaraujo/angular2_cheatsheet_dart)
* [Чек-лист Angular Performance](https://github.com/mgechev/angular-performance-checklist)

<h3 id="angular-ui">UI библиотеки</h3>

<h4 id="material">Material Design</h4>

* [Официальный репозиторий Angular Material Design (GitHub)](https://github.com/angular/material2)
* [Коллекция Material Design компонентов (md2)](https://github.com/Promact/md2) 
* [Коллекция компонентов на основе материала Material Design Lite (angular2-mdl)](https://www.npmjs.com/package/angular2-mdl) 
* [Компоненты, созданные с помощью Google Material Design Lite framework (mdl-ext)](https://www.npmjs.com/package/mdl-ext)
* [Компоненты Materialize library (ng2-materialize)](https://github.com/sherweb/ng2-materialize)
* [Material Light](https://github.com/YagoLopez/material-light) 
* [Легковесная библиотека на основе Material Design](https://github.com/src-zone/material)


<h3 id="features">Важные особенности</h3>

<h4 id="components">Компоненты</h4>

Компонент управляет отображением представления на экране, в ее основе используется Shadow DOM по умолчанию (для создания инкапсулированного визуального поведения). Как правило, компоненты используются для создания простого виджета в пользовательском интерфейсе, в то же время они могут представлять из себя набор еще более простых компонентов внутри себя (для увеличения абстракции и создания простых функциональных виджетов внутри приложения).

```js
@Component({
  selector: 'html-name-element'
})
export class MyComponent {
  // ...
}
```

<h4 id="templates">Шаблоны</h4>

Шаблон - это ваша html-разметка, в которой вы можете описывать ваши взаимодействия с DOM на основе модели данных и событий вашего класса компонента (в примере, контроллер MyComponent).

```js
@Component({
 template: 'my-component.component.html'
})
export class MyComponent {
 
  public title: string = "Hello world";
  
  // ..

}
```

```html
<!-- my-component.component.html -->
<p>
  Интерполяция: {{ title }},  
  или так:      {{ this.title }}
</p>
```

<h4 id="change-detection">Обнаружение изменений</h4>

Каждый компонент имеет свой собственный детектор изменений, который гарантирует проверку привязок данных, определенных шаблоне.

<h4 id="dependency-injection">Внедрение зависимостей</h4>

Внедрение зависимостей (англ. Dependency Injection) — это композиция структурных шаблонов проектирования, при которой за каждую функцию приложения отвечает один, условно независимый объект (сервис), который может иметь необходимость использовать другие объекты (зависимости), известные ему интерфейсами. Зависимости передаются (внедряются) сервису в момент его создания.


```js
// logger.service.ts
@Injectable()
export class LoggerService {
  // ..
  
  public get trace() {
    return console.debug.bind(console);
  }
  
}
```

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {
 
  constructor(private logger: LoggerService) {
    logger.trace('Init MyComponent');
  }

}
```

<h4 id="directives">Директивы</h4>

Директивы позволяют получать прямой доступ к DOM ваших элементов. Они бывают двух видов: структурные и атрибутные.

Атрибутная директива:

```js
@Directive({
  selector: '[bold]'
})
export class BoldDirective{
     
    constructor(private elementRef: ElementRef){
        this.elementRef.nativeElement.style.fontWeight = "bold";
    }
}
```

Здесь внедряется сервис "ElementRef". Он представляет ссылку на элемент, к которому будет применяться директива:


```html
<!-- my-component.component.html -->
<p bold>Hello world</p>
```

Структурные директивы:

Структурные директивы изменяют структуру DOM с помощью добавления или удаления html-элементов. Существует минимум три встроенных структурных директивы: ngIf, ngSwitch и ngFor.

```js
@Component({ /* ... */ })
export class AppComponent {
    // ..
    
    public items = ["Apple iPhone", "Huawei Mate", "Samsung Galaxy", "Motorola Moto Z"];
}
```

```html
<!-- my-component.component.html -->
<ul>
  <li *ngFor="let item of items">{{item}}</li>
</ul>
```

<h4 id="pipes">Пайпы</h4>

Пайп (pipe) представляет собой особый обработчик, который позволяет форматировать отображаемые значения

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {
  public fields = [ { id: 1 }, { id: 2 } ];
}
```

```html
<!-- my-component.component.html -->
Читаемый вывод объекта: 
<pre> {{ fields | json }} </pre>
```

Помимо стандартных, вы можете писать собственные

```js
@Pipe({ name: 'factorial' })
export class FactorialPipe implements PipeTransform {
  transform(value: number, args?: any): number {
    if(value<=0) return 0;
     
    let result = 1;
    for(let i=1; i<=value; i++){
        result = result * i;
    }
    
    return result;
  }
}
```

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {
  public x = 5;
}
```

```html
<!-- my-component.component.html -->
Факториал числа {{ x }} равен {{ x | factorial }}
<!-- Факториал числа 5 равен 120 -->
```

<h4 id="web-workers">Web Workers</h4>

Поддержка Web Worker в Angular предназначена для упрощенного распараллеливания в вашем приложении. Когда ваше приложение запускается, Angular проводит всю основную работу по обработке вашей логики в отдельных потоках, ядро выполняет вычисление в своем рабочем потоке, в то время как другие функции могут и вовсе выполняться не в потоках.

<h4 id="http">HTTP</h4>

Самый распространенный способ получить данные от web-служб — это через HttpClient сервис доступный для внедрения зависимостей в ваших компонентах. Angular HttpClient довольно прост. Все, что нам нужно сделать, это вызвать метода get и передать ему url. Данный метод get возвращает объект Observable. Этот класс является частью библиотеки rxjs, которая используется во многих местах Angular'а.

```js
// rest.service.ts
@Injectable()
export class RestService {

  constructor(private httpClient: HttpClient) {}
  
  public getByObservable(url: string): Observable<any> {
      return this.httpClient.get(url);
  }
  
  public getByPromise(url: string): Promise<any> {
      return this.httpClient.get(url).toPromise();
  }
 
}
```

Подобно обещанию (Promise), наблюдатель (Observable) не содержит в себе сразу значения. Вместо этого у него есть метод подписки(subscribe), где мы можем зарегистрировать обратный вызов(callback). Этот callback вызывается, как только результат будет доступен. Помимо обещания, Observable может вернуть более одного значения. Вы можете вернуть себе поток результатов. Но это не имеет значения в данном случае. В нашем случае Observable возвращает только одно значение.

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {

  constructor(private rest: RestService) {}
  
  // Observable classic examples
  public getFields() {
    this.rest.getByObservable('http://anyurl.com').subscibe(value =>{
      // value - результат
    },
    error => {
      // error - объект ошибки
    });
  }
  
  // Promise classic examples
  public async getAsyncField() {
    try {
      // value - результат
      const value = await this.rest.getByPromise('http://anyurl.com');
    } catch (error) {
      // error - объект ошибки
    }
  }
  
}
```

<h4 id="router">Роутинг</h4>

* [Официальная документация Router](https://angular.io/guide/router.html#sts=Router%20imports)
* [ui-router](https://github.com/angular-ui/ui-router)

<h4 id="test">Тестирование</h4>

* [Тестирование Http сервиса с Jasmine](http://chariotsolutions.com/blog/post/testing-http-services-angular-2-jasmine/)
* [UI-тестирование компонентов с TestComponentBuilder](http://chariotsolutions.com/blog/post/testing-angular-2-components-unit-tests-testcomponentbuilder/)

<h4 id="aot">Ahead-of-Time компиляция</h4>

* [Официальная документация](https://angular.io/guide/aot-compiler)
* [AOT в Angular](http://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)
* [Сборка Angular приложения для продакшина](http://blog.mgechev.com/2016/06/26/tree-shaking-angular2-production-build-rollup-javascript/)
* [Прояснения в Ahead-Of-Time компиляции в Angular](http://slides.com/wassimchegham/demystifying-ahead-of-time-compilation-in-angular-2-aot-jit)
* [Несколько решений по работе с Ahead of Time (AOT)](https://blog.craftlab.hu/multiple-solutions-for-angular-ahead-of-time-aot-compilation-c474d9a0d508)
* [Пример кода с Webpack и AOT](https://github.com/blacksonic/angular2-aot-webpack)
* [Пример кода с Rollup и AOT](https://github.com/mgechev/angular2-ngc-rollup-build)


### Angular CLI
* [Официальный сайт](https://cli.angular.io/)
* [Официальный репозиторий](https://github.com/angular/angular-cli)

<h3 id="webpack">Webpack стартеры</h3>

* [Официальный сайт Webpack](https://webpack.js.org)
* [Angular Webpack стартер от PatrickJS](https://github.com/gdi2290/angular-starter)
* [Angular Webpack стартер от Preboot](https://github.com/preboot/angular-webpack)
* [Angular Nightly Webpack стартер](https://github.com/qdouble/angular-webpack2-starter)
* [Angular Webpack стартер с ASP.NET Core от Damien Bowden](https://github.com/damienbod/AngularWebpackVisualStudio)
* [Webpack конфигурация для Angular разработки от ng-seed](https://github.com/ng-seed/angular-webpack-config)

<h3 id="series">Публикации</h3>

* Ionic
  * Angular
    * [Введение](http://blog.ionic.io/angular-2-series-introduction/)
    * [Компоненты](http://blog.ionic.io/angular-2-series-components/)
* Auth0
  * Angular
    * [Работаем c пайпами (pipes)](https://auth0.com/blog/angular2-series-working-with-pipes/)
    * [Паттерн проектирования Domain Model and Dependency Injection](https://auth0.com/blog/angular-2-series-part-2-domain-models-and-dependency-injection/)
    * [Создание Desktop приложения на Angular 2 и Electron](https://auth0.com/blog/create-a-desktop-app-with-angular-2-and-electron/)
* thoughtram
  * Angular Template Syntax
    * [Введение](https://blog.thoughtram.io/angular/2015/08/11/angular-2-template-syntax-demystified-part-1.html)
* [letsboot.com](https://medium.com/letsboot)
  * Test Driven Development
    * [Angular TDD, Karma, Jasmine, PhantomJS, Gitlab-CI](https://medium.com/letsboot/angular-4-and-testing-angular-cli-gitlab-ci-ng-test-phantomjs-tdd-afc20f50b928)
  * Angular and Firebase
    * [Учимся настраивать и работать AngularFire](https://medium.com/letsboot/lets-learn-how-to-install-and-setup-angularfire2-4-0-135d72bb0a41)

<h3 id="video-tutorials">Видеоуроки</h3>

* [Egghead.io - Angular](https://egghead.io/technologies/angular2)
* [Egghead.io - Разработка приложения на Angular + Redux](https://egghead.io/courses/building-a-time-machine-with-angular-2-and-rxjs)
* [HiRez.io - Angular: основы](https://www.hirez.io/c/angular-basics-1/e/episode-1-course-overview)
* [HiRez.io - Angular: введение в компоненты](https://www.hirez.io/c/components-1/e/episode-1-course-overview)
* [Udemy - Введение в Angular](https://www.udemy.com/introduction-to-angular2/)
* [Udemy - Angular и TypeScript для начинающих](https://www.udemy.com/angular-2-tutorial-for-beginners/)
* [Udemy - Курс по Angular](https://www.udemy.com/the-complete-guide-to-angular-2/)
* [Pluralsight - Angular: обзор](https://www.pluralsight.com/courses/angular-2-first-look)
* [Pluralsight - Angular 2: Getting Started](https://www.pluralsight.com/courses/angular-2-getting-started-update)
* [Channel9 - Будущее TypeScript](https://channel9.msdn.com/Events/Build/2015/3-644)
* [Channel9 - Создание кроссплатформенных приложений с Angular](https://channel9.msdn.com/Events/Build/2016/T627)
* [Code School - Разгоняем Angular](https://www.codeschool.com/courses/accelerating-through-angular)
* [Angular - типизированное хранилище](https://www.youtube.com/watch?v=bEkPEnudm7s&feature=youtu.be)
* [Angular - расширенные советы и рекомендации](https://www.youtube.com/watch?v=vyiyJCLlGwo&feature=youtu.be)
* [Angular Fullstack](https://www.youtube.com/channel/UCRefxaAA-7PfezH3CY87fzw)
* [Angular Master Class](https://www.udemy.com/angular-crash-course-for-beginners)

<h3 id="style-guides">Стайл-гайды</h3>

* [Официальный Angular Style guide](https://angular.io/guide/styleguide)
* [Описание того, как нужно составлять правила для TSLint](https://github.com/ng-seed/angular-tslint-rules)

<h3 id="angular-connect">Angular Connect конференция</h3>

* [Основной доклад – Brad Green, Igor Minar and Jules Kremer](https://www.youtube.com/watch?v=UxjgUjVpe24)
* [Стратегии тестирования Angular – Julie Ralph](https://www.youtube.com/watch?v=C0F2E-PRm44)
* [Создание нативных мобильных приложений с Angular and NativeScript​ - Sebastian Witalec](https://www.youtube.com/watch?v=4SbiiyRSIwo)
* [Angular Data Flow – Jeff Cross, Rob Wormald and Alex Rickabaugh](https://www.youtube.com/watch?v=bVI5gGTEQ_U)
* [Стратегии итеративных обновлений больших Angular-приложений – Jen Bourey](https://www.youtube.com/watch?v=8tGcdaItj0I)
* [Отладка Angular приложений с ипсользованием Batarangle – Yuri Takhteyev and Igor Krivanov](https://www.youtube.com/watch?v=cAC4d3KIQcM)
* [Разработка приложений с Firebase and Angular - Sara Robinson](https://www.youtube.com/watch?v=RD0xYicNcaY)
* [Концепции Angular - Victor Savkin and Tobias Bosch](https://www.youtube.com/watch?v=4YmnbGoh49U)
* [Модульность Angular приложений – Pawel Kozlowski](https://www.youtube.com/watch?v=9odY9Rh5kTQ)
* [Создание приложений реального времени на Angular и Meteor - Uri Goldshtein](https://www.youtube.com/watch?v=3FT0BqYASCo)

<h3 id="books">Книги</h3>

* [ng-book 2](https://www.ng-book.com/2/) `fullstack.io`
* [Как стать ниндзя в Angular](https://books.ninja-squad.com/angular) `Ninja Squad`
* [Angular разработка с TypeScript](https://www.manning.com/books/angular-2-development-with-typescript) `Manning Publications`
* [Angular в бою](https://www.manning.com/books/angular-in-action) `Manning Publications`
* [Практики Angular](https://leanpub.com/practical-angular-2) `Leanpub`
* [Переходим на Angular](https://www.packtpub.com/web-development/switching-angular-2) `Packt Publishing`
* [Angular тренинги](https://www.gitbook.com/book/rangle-io/ngcourse2/details) `Rangle.io`
* [Изучаем Angular](http://learnangular2.com/) `Ionic Team`
* [Тестирование Angular приложений](https://www.manning.com/books/testing-angular-applications) `Manning Publications`

<h3 id="on-site-training">Онлайн тренинги</h3>

* [AngularClass](https://angularclass.com)
* [Angular Boot Camp](https://angularbootcamp.com)
* [thoughtram](http://thoughtram.io/training.html)
* [Egghead.io](https://egghead.io/angularjs-enterprise-training-workshop)
* [ng-book](https://www.ng-book.com/2/)
* [Angular Workshop](http://chariotsolutions.com/course/angular-workshop-fundamentals-architecture/)
* [Web Age Solutions](http://www.webagesolutions.com/courses/WA2533-introduction-to-angular-2-programming)
* [Letsboot.com](https://www.letsboot.com/angular-2-in-house-training-support)
* [Free on-site 2-days training delivered by SFEIR (in France)](https://school.sfeir.com/project/sa200/)


<h3 id="approach-and-explanation">Различные подходы</h3>

* Victor Savkin
  * [Внедрение зависимостей (DI) в AngularJS и Angular](https://vsavkin.com/dependency-injection-in-angular-1-and-angular-2-d69589979c18)
  * [Пишем на Angular с Typescript](https://vsavkin.com/writing-angular-2-in-typescript-1fa77c78d8e8)
  * [Angular - синтаксис шаблонов](https://vsavkin.com/angular-2-template-syntax-5f2ee9f13c6a)
  * [Концепция The Core Concepts of Angular 2](https://vsavkin.com/the-core-concepts-of-angular-2-c3d6cbe04d04)
  * [Основные файзы при разработке на Angular](https://vsavkin.com/two-phases-of-angular-2-applications-fda2517604be)
  * [Стратегии обнаружения в Angular](https://vsavkin.com/change-detection-in-angular-2-4f216b855d4c)
  * [Поддержка функционального программирования](https://vsavkin.tumblr.com/post/108837493941/better-support-for-functional-programming-in)
  * [Angular: унифицированный Dependency Injection](https://vsavkin.tumblr.com/post/102965317996/angular-2-bits-unified-dependency-injection)
  * [Angular Router](https://vsavkin.com/angular-2-router-d9e30599f9ea)

* AngularClass
  * [Автоматизированное развертывание приложений на Angular и Webpack](https://angularclass.com/blog/automated-angular-2-conventions-with-webpack/)
  * [Angular для AngularJS разработчиков](https://angularclass.com/blog/angular-2-for-angularjs-developers/)
  * [Angular 2 для ReactJS разработчиков](https://angularclass.com/blog/angular-2-for-react-developers/)

* thoughtram
  * [Разработка компонента tabs (вкладки) в Angular](https://blog.thoughtram.io/angular/2015/04/09/developing-a-tabs-component-in-angular-2.html)
  * [Разработка zippy-компонента в Angular](https://blog.thoughtram.io/angular/2015/03/27/building-a-zippy-component-in-angular-2.html)
  * [Введение в сервисы в Angular](https://blog.thoughtram.io/angular/2015/09/17/resolve-service-dependencies-in-angular-2.html)
  * [Forward references в Angular](https://blog.thoughtram.io/angular/2015/09/03/forward-references-in-angular-2.html)
  * [Видимость в DI в Angular 2](https://blog.thoughtram.io/angular/2015/08/20/host-and-visibility-in-angular-2-dependency-injection.html)
  * [Dependency Injection in Angular 2](https://blog.thoughtram.io/angular/2015/05/18/dependency-injection-in-angular-2.html)
  * [Routing in Angular 2 **Depreciated**](https://blog.thoughtram.io/angular/2015/06/16/routing-in-angular-2.html)
  * [Routing in Angular 2 Revisited](https://blog.thoughtram.io/angular/2016/06/14/routing-in-angular-2-revisited.html)
  * [Angular 2 Template Syntax Demystified - Part 1](http://blog.thoughtram.io/angular/2015/08/11/angular-2-template-syntax-demystified-part-1.html)
  * [View Encapsulation in Angular 2](https://blog.thoughtram.io/angular/2015/06/29/shadow-dom-strategies-in-angular2.html)
  * [Styling Angular 2 components](https://blog.thoughtram.io/angular/2015/06/25/styling-angular-2-components.html)
  * [Even better ES5 code for Angular 2](https://blog.thoughtram.io/angular/2015/07/06/even-better-es5-code-for-angular-2.html)
  * [Writing Angular 2 code in ES5](https://blog.thoughtram.io/angular/2015/05/09/writing-angular-2-code-in-es5.html)
  * [The difference between Annotations and Decorators](https://blog.thoughtram.io/angular/2015/05/03/the-difference-between-annotations-and-decorators.html)

* Hristo Georgiev
  * [Debugging Angular 2 Applications](https://www.pluralsight.com/guides/front-end-javascript/debugging-angular-2-applications)

* Helgevold Consulting
  * [Web Workers in Angular 2.0](http://www.syntaxsuccess.com/viewarticle/web-workers-in-angular-2.0)
  * [Creating a Virtualized Grid](http://www.syntaxsuccess.com/viewarticle/virtualized-spreadsheet-component-in-angular-2.0)
  * [Socket.io with Observables](http://www.syntaxsuccess.com/viewarticle/socket.io-with-rxjs-in-angular-2.0)
  * [Change Detection](http://www.syntaxsuccess.com/viewarticle/change-detection-in-angular-2.0)

* Burak Tasci (fulls1z3)
  * [Angular 4 with server side rendering (aka Angular Universal)](https://medium.com/burak-tasci/angular-4-with-server-side-rendering-aka-angular-universal-f6c228ded8b0)
  
