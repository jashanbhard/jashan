 <!================================Code for cshtml================================>
<td>
                                        <label class="fs-6 fw-semibold mb-2">Type Of Leave</label>
                                        <select class="form-select form-select-solid select2-hidden-accessible" data-control="select2" data-hide-search="true" data-                      placeholder="Select a Team Member" name="target_assign" data-select2-id="select2-data-16-1frb" tabindex="-1" aria-hidden="true" data-kt-initialized="1">
                                            <option value="" data-select2-id="select2-data-18-p5cm">Select Type Of Leave...</option>
                                            @foreach (var item2 in Model.leaves)
                                           {
                                            <option value="1">@item2.TypeOfLeave</option>
                                                <option value="1">@item.Status</option>
                                            }
                                        </select>                                        
                                        </td>
<!==============================Apply at the bottom of cshtml==========================>

<script>
    $(function () {
        $('#datepicker').datepicker();
        $('#datepickerto').datepicker();
    });
</script>

<!==========================Code for Layout/Default cshtml============================>

 <link href="https://code.jquery.com/ui/1.12.1/themes/ui-lightness/jquery-ui.css"
          rel="stylesheet" />

    <!-- ✅ load jQuery ✅ -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"
            integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4="
            crossorigin="anonymous"></script>

    <!-- ✅ load jquery UI ✅ -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js"
            integrity="sha512-uto9mlQzrs59VwILcLiRYeLKPPbS/bT71da/OEBYEwcdNUk8jYIy+D176RYoop1Da+f9mvkYrmj5MCLZWEtQuA=="
            crossorigin="anonymous"
            referrerpolicy="no-referrer"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
