.. _conferences:

Attending Conferences
=====================

Creating a poster
~~~~~~~~~~~~~~~~~
Here are some helpful tips!

1. Always check the size requirements before starting! It's generally a good idea to specify these dimensions as the canvas size in your graphics software
2. Leave at least 0.5 inches of padding on all sides of your poster just in case the printer requires it
3. When placing figures onto your poster, try to use vector image formats (.svg, .pdf, etc) rather than raster formats (.png, .jpg, etc).

    .. figure:: https://github.com/gymrek-lab/gymreklab.github.io/assets/23412689/4f1a241a-f47f-4702-8719-76026161f31c
        :alt: Raster vs vector images
        :align: center
        :width: 400px

    a. Raster is the traditional format that you're probably familiar with. It stores colors for each pixel in your image. By contrast, vector formats store each component of your figure as an object. For example, a line in your image will be defined in vector format by a start position, end position, and color -- rather than a series of black pixels.
    b. If you place a raster image on your poster, there's a good chance it will appear blurry when printed. The advantage of vector formats is that they can be rescaled to any arbitrary size and will never appear blurry!
    c. If you use matplotlib or pandas to create your figures, you can easily just change the desired output filename from ".png" to ".pdf" to create a vector version of the figure.

    .. warning::
        Some images (like Manhattan plots) will have so many objects in them that Adobe Illustrator will freeze and crash when you try to load them. For situations like these, it's best to import them as PNG. To minimize blurrines, you can try to recreate the figure with a high DPI (or PPI) and then resize it down within Illustrator.

4. When creating your poster, try to use software that will allow you to work with vector (as opposed to raster) images. So don't use google slides/drawings! Adobe illustrator is probably the best option. You can ask Dorit to get you a license. After you're done, export your poster as a PDF rather than a PNG.
5. You can find some old lab posters in `the lab's Google Drive <https://drive.google.com/drive/folders/1ora8McmJShuJeiwb1hCSrsKWEiMoAxCs>`_.

    .. note::
        Please consider uploading your poster here after you're done with it so that future years can look back on it and glean wisdom! Also, never think that your poster isn't good enough to be shared here! The best way to communicate an idea will always depend on its content, after all. You never know who might be inspired by the design of your poster one day.

6. Our logos can be found in `the lab Google Drive <https://drive.google.com/drive/folders/1-egL2EVfTh7wH4wmfFcruGtJMplnPVQQ>`_. For UCSD's, you can refer to `this Jacobs School of Engineering webpage <https://jacobsschool.ucsd.edu/logos>`_. Also, consider displaying your email and a QR code link to your GitHub repo or documentation.
7. The cheapest place to print posters is probably on campus at the print shop at `UCSD Campus Curbside Pickup <https://maps.app.goo.gl/FseyUa62wk3Qztu5A>`_. You can request reimbursement as part of your conference expenses afterwards.
    a. Go to `their online portal <https://ucsdimprints.myprintdesk.net/DSF/SmartStore.aspx?6xni2of2cF2gL05u6lNHBp6AwVlPfgDQIgaPc5Cokq4RKYVvn2cx3C2V0adSszgU#!/CategoryHome/9>`_ to create an order and submit a PDF of your poster. (Use `this link <https://blink.ucsd.edu/facilities/tritonprint/index.html>`_ to navigate to the portal if the former doesn't work.)
    b. After logging in, click on "Signs and Banners" and then "BUY NOW" under the category: "POSTERS, CHARTS, AND DISPLAYS".

        .. figure:: https://github.com/gymrek-lab/gymreklab.github.io/assets/23412689/efd10f1d-c2d6-42ab-a97f-57eb1a8d79af
            :alt: Navigating the online print shop portal
            :align: center
            :width: 400px

    c. Make sure to specify the right number of pages, the size, and the media (recommended: 36 Lb Heavyweight Coated Bond):

        .. figure:: https://github.com/gymrek-lab/gymreklab.github.io/assets/23412689/3f794299-7690-4f1a-b9f0-4e2c9dc067e1
            :alt: Poster print settings 1
            :align: center
            :width: 400px

        .. figure:: https://github.com/gymrek-lab/gymreklab.github.io/assets/23412689/08a5faad-43ed-4a27-ac76-629821288bb4
            :alt: Poster print settings 2
            :align: center
            :width: 400px

    d. After submitting the order, call them to ask when to pick it up.
