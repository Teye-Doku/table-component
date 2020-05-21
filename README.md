# table-component
# App component which is the root of the application will house the table component
# the table component also comprises of the MultipleRowData and RenderSingleRow
# the MultipleRowData component is a direct child of the Table Component which renders a multiple rows of RenderSingleRow component
# the RenderSingleRow component is a direct child of the the MultipleRowData which renders a single table row
# the table component receives data which is props from the App component which inturn is passed on to the MultipleRowData component
# Upon looping the a single item is passed to the RenderSingleRow data.
