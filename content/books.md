+++
title = 'Books'
menu = "main"
date = "2025-01-16T12:00:00+01:00"

tags = ["books"]
+++

# Books

I use Goodreads (I know) to track what I read.
You can follow me there: https://www.goodreads.com/zurdala

Currently, this book is on my nightstand:

{{< rawhtml >}}
<div style="width: 100%; display: flex; flex-direction: column; min-height: 100px">
      <style type="text/css" media="screen">
        .gr_grid_container {
          position: relative; /* Positioning context for the pseudo-element */
          display: inline-block; /* Allow the book to size to the image */
          width: 200px;
          perspective: 1000px;
        }
        .gr_grid_book_container {
          /* customize book cover container div here */
          float: left;
          width: 80px;
          height: auto;
          overflow: hidden;
          box-shadow: 0 0px 0px rgba(0, 0, 0, 0.5); /* Shadow effect */
          transform: rotateY(-10deg); /* Slightly rotate to give a 3D effect */
          transition: transform 0.3s; /* Smooth transition for hover effect */
        }
        .gr_grid_book_container:hover {
            transform: rotateY(0deg); /* Reset rotation on hover */
        }
        .gr_grid_book_container::before {
            content: ''; /* Required for pseudo-element */
            width: 50px; /* Width of the spine */
            height: 100%; /* Match the height of the image */
            background-color: #f5e9c0ff; /* Color of the spine (brown) */
            position: absolute; /* Position it relative to the book container */
            left: 100px; /* Align to the left of the image */
            transform: rotateY(-10deg); /* Match the rotation of the image */
            z-index: -1; /* Ensure the spine is above the image */
        }
      </style>
      <script src="https://www.goodreads.com/review/grid_widget/100918725.reading%20book%20montage?cover_size=medium&hide_link=true&hide_title=true&num_books=1&order=d&shelf=currently-reading&sort=date_updated&widget_id=1737052414" type="text/javascript" charset="utf-8"></script>
</div>
{{< /rawhtml >}}

And below, it follows a list of my most recent reads.

{{< rawhtml >}}
<div style="width: 100%; display: flex; flex-direction: column; min-height: 100px">
      <style type="text/css" media="screen">
        .gr_grid_container {
          width: 100%;
        }
        .gr_grid_book_container {
          /* customize book cover container div here */
          float: left;
          width: 98px;
          height: 160px;
          padding: 2px 3px;
          overflow: hidden;
        }
      </style>
      <script src="https://www.goodreads.com/review/grid_widget/100918725.Recent%20reads?cover_size=medium&hide_link=true&hide_title=true&num_books=21&order=d&shelf=read&sort=date_read&widget_id=1737056302" type="text/javascript" charset="utf-8"></script>
</div>
{{< /rawhtml >}}

Drop me an email if you want to comment any books we have both read.
I am always happy to talk about books and where to find them (cozy bookshops)!

_PS: If JavaScript is disabled, the book covers will not load, so it is better to head to my profile instead._
