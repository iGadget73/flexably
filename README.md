# flexably
A scss template for a configurable flexbox css grid

## options
- full control over every class name in the grid
- simple array for sizes
- hidden classes included


## usage
here's a simple example that will show `.my-container-…` with full width **before** and two columns **after breakpoint *m*.**

*(works just with default values):*

    <div class="grid">
        <div class="my-container-1 col-xs-12 col-m-6">…</div>
        <div class="my-container-2 col-xs-12 col-m-6 grid">
            <div class="col-xs-12 col-s-6 col-m-4 col-l-2 col-xl-1">…</div>
        </div>
    </div>
