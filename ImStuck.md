Github

// Github search
topic:<things> search


Rails

// To view javascript in rails
$(document).on('turbolinks:load', function() {
  // Your code here
});

// To add icon in the application
'Add icon to app/assets/images/favicon'
app/assets/images/favicon
'Add this line of code in application.html.erb file'
<%= favicon_link_tag %>

// To change column type and name
$ rails g migration <table_name>
db/migrate/file
def change
  change_column :your_table, :your_column, :text
  rename_column :table, :old_column, :new_column
end

// To add column to an existing table
$ rails generate migration <add_fieldname_to_tablename fieldname:string>
example
$ rails g migration <add_email_to_users email:string>
$ rails db:migrate

// To delete column from existing table
$ rails g migration <table_name>
def change
  remove_column :table_name, :column_name
end



NodeJS

// To show all JS Variables in the terminal
$ node
$ global
or
$ window   // In the browser
