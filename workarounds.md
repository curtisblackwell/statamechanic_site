# Numbered Entries
## Slug
### nav_sidebar.html
    {{ replace find="[0-9]*\." regex="yes" }}{{ slug }}{{ /replace }

should be

    {{ slug }}

### layouts/default.html
    {{ replace find="[0-9]*\." regex="yes" }}{{ slug }}{{ /replace }

should be

    {{ slug }}