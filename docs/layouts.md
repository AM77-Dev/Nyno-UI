# Layouts

## Containers

Containers are the most basic layout element in Bootstrap and are required when using our default grid system.

### Container
``` html
<div class="container">
  <!-- Content here -->
</div>
```

### Small Container
``` html
<div class="container small-container">
  <!-- Content here -->
</div>
```

### Large Container
``` html
<div class="container large-container">
  <!-- Content here -->
</div>
```

## Grid System

A flexbox grid to build layouts of all shapes and sizes thanks to a twelve column system.

### Row & Cols

#### col-1
``` html
<div class="row">
  <div class="col col-1">
    <!-- Content here -->
  </div>
</div>
```

<div class="row">
  <div class="col col-1" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-11" style='background:#333333; padding: 20px'></div>
</div>

#### col-2
``` html
<div class="row">
  <div class="col col-2">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-2" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-10" style='background:#333333; padding: 20px'></div>
</div>

#### col-3
``` html
<div class="row">
  <div class="col col-3">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-3" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-9" style='background:#333333; padding: 20px'></div>
</div>

#### col-4
``` html
<div class="row">
  <div class="col col-4">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-4" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-8" style='background:#333333; padding: 20px'></div>
</div>

#### col-5
``` html
<div class="row">
  <div class="col col-5">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-5" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-7" style='background:#333333; padding: 20px'></div>
</div>

#### col-6
``` html
<div class="row">
  <div class="col col-6">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-6" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-6" style='background:#333333; padding: 20px'></div>
</div>

#### col-7
``` html
<div class="row">
  <div class="col col-7">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-7" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-5" style='background:#333333; padding: 20px'></div>
</div>

#### col-8
``` html
<div class="row">
  <div class="col col-8">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-8" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-4" style='background:#333333; padding: 20px'></div>
</div>

#### col-9
``` html
<div class="row">
  <div class="col col-9">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-9" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-3" style='background:#333333; padding: 20px'></div>
</div>

#### col-10
``` html
<div class="row">
  <div class="col col-10">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-10" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-2" style='background:#333333; padding: 20px'></div>
</div>

#### col-11
``` html
<div class="row">
  <div class="col col-11">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-11" style='background:#E0E0E0; padding: 20px'></div>
  <div class="col col-1" style='background:#333333; padding: 20px'></div>
</div>

#### col-12
``` html
<div class="row">
  <div class="col col-12">
    <!-- Content here -->
  </div>
</div>
```
<div class="row">
  <div class="col col-12" style='background:#212121; padding: 20px'></div>
</div>

### nested rows
``` html
<div class="row">
  <div class="col col-9">
    <div class="row">
      <div class="col col-4">
        <!-- Content here -->
      </div>
      <div class="col col-8">
        <div class="row">
          <div class="col col-10">
            <!-- Content here -->
          </div>
          <div class="col col-2">
            <!-- Content here -->
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```
<div class="row">
  <div class="col col-9" style='background:#E0E0E0; padding: 10px'>
    <div class="row">
      <div class="col col-4" style='background:#212121; padding: 10px'></div>
      <div class="col col-8" style='background:#999999; padding: 10px'>
        <div class="row">
          <div class="col col-10" style='background:#000000; padding: 20px'></div>
          <div class="col col-2" style='background:#dddddd; padding: 20px'></div>
        </div>
      </div>
    </div>
  </div>
</div>

### Offsets
Move columns to the right using .offset-* classes. These classes increase the left margin of a column by * columns
```html
<div class="row">
  <div class="col col-2"></div>
  <div class="col col-3 col-offset-2"></div>
  <div class="col col-2"></div>
  <div class="col col-2 col-offset-1"></div>
</div>
```

<div class="row">
  <div class="col col-2" style='background:#000000; padding: 20px'></div>
  <div class="col col-3 col-offset-2" style='background:#dddddd; padding: 20px'></div>
  <div class="col col-2" style='background:#333333; padding: 20px'></div>
  <div class="col col-2 col-offset-1" style='background:#000000; padding: 20px'></div>
</div>