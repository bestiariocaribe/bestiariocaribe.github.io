# this would be part of the yml

# Naming file: 
# prepend date and monstertype '2018-05-15-zombis-

prose:

rooturl: '_posts/zombis'
media: 'images'
metadata:
  _posts/zombis:

   - name: "title"
   field:
   element: "text"
   label: "Title"
   placeholder: "Enter your title"
   value: ""

   - name: "layout"
   field:
   element: "hidden"
   value: "article"

   - name: "author"
   field:
   element: "hidden"
   value: "group5"

   - name: "modified"
   field:
   element: "hidden"
   value: CURRENT_DATETIME

   - name: "image_teaser"
   field:
   element: "hidden"
   value: ""

   - name: "storymap_id"
   field:
   element: "text"
   label: "Storymap ID"
   placeholder: "example: 772f6677de9353fe75919801ec1cb48b"
   help: "If including a Storymap, enter the string of characters included in your Storymap project URL"
   value: ""

   - name: "storymap_title"
   field:
   element: "text"
   label: "Storymap title"
   placeholder: "ejemplo: Los zombis en los videojuegos"
   help: "If including a Storymap, enter the title associated with your Storymap project"
   value: ""

   - name: "timeline_id"
   field:
   element: "text"
   label: "Timeline ID"
   placeholder: "example: 1uGjhA8mK551YwHW1wRF5sh1utOxDV73JfuJbILe2jOI"
   help: "If including a Timeline, enter the string of characters included in your Timelinejs project URL"
   value: ""

   - name: "published"
   field:
   element: "checkbox"
   label: "Publish?"
   help: "Check the box when ready to publish"
   value: false
