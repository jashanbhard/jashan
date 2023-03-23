 <!--Code for cshtml-->
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
<!--Apply at the bottom of cshtml-->

<script>
    $(function () {
        $('#datepicker').datepicker();
        $('#datepickerto').datepicker();
    });
</script>

<!--Code for Layout/Default cshtml-->
