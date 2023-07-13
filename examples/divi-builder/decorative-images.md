# Marking Images as Decorative in the Divi Builder
Normally leaving an empty `alt=""` tag is sufficient, but it is possible to apply the `aria-hidden="true"` attribute using the Divi Builder in WordPress to denote a decorative image.

1. Edit the module or element: In the Divi Builder, locate the module or element that contains the image you want to mark as decorative.
   
2. Access the module settings: Click on the module or element to open its settings.
   
3. Find the HTML Attributes option: Depending on the version of Divi you are using, this option may be available under the "Advanced" tab or the "Custom CSS" tab within the module settings.
   
4. Add the `aria-hidden` attribute: In the HTML Attributes field, add `aria-hidden="true"` as a custom attribute. This will tell assistive technologies to ignore the element and its contents.
   
5. Save and update: Save the changes to the module or element, and update the page or post.

By applying `aria-hidden="true"` to the module or element containing the image, you are indicating that the image is decorative and doesn't convey any important information. This helps improve the accessibility of your website for users of assistive technologies.

Please note that the specific steps may vary slightly based on the version of Divi you are using, but the general concept of adding custom attributes should be applicable across versions.