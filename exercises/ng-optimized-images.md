# NgOptimizeImages

In this exercise you will learn how to optimize images using the NgOptimizeImages Directive

## Using ngSrc 

Change the src attribute of the image tag in the movie card component to ngSrc and add a height and width: 

<details>
    <summary>show solution</summary>

Go to `movie-card.component.html` and modify its attributes to use ngSrc

```html
  <img class="movie-image"
       [alt]="movie.title"
       [ngSrc]="movie.poster_path | movieImage"
       height="330"
       width="220"
  >
```
</details>

Now open up the console and view the errors 

![img.png](images/ng-optimize-image/ng-image-prio-warning.png)

