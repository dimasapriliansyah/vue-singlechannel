<template>
  <div class="sidebar-group">
    <!-- Chats sidebar -->
    <div id="right-content" class="sidebar active">
      <header class="bg-green" style="padding:10px 10px 0px 14px">
        <ul class="nav nav-tabs" role="tablist">
          <li class="nav-item">
            <a
              class="nav-link active text-center"
              data-toggle="tab"
              href="#profile"
              role="tab"
              aria-controls="profile"
              aria-selected="true"
            >
              <i class="fa fa-user md18"></i>
              <br />Profile
            </a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link text-center"
              data-toggle="tab"
              href="#cwc"
              role="tab"
              aria-controls="cwc"
              aria-selected="false"
            >
              <i class="fa fa-pencil-square-o md18"></i>
              <br />CWC
            </a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link text-center"
              data-toggle="tab"
              href="#journey"
              role="tab"
              aria-controls="journey"
              aria-selected="false"
            >
              <i class="material-icons">timeline</i>
              <br />Journey
            </a>
          </li>
        </ul>
      </header>
      <div class="sidebar-body" tabindex="6" style="overflow: hidden; outline: none;">
        <ul class="list-group list-group-flush">
          <div class="tab-content mt-3">
            <div class="tab-pane show active text-center p0" id="profile" role="tabpanel">
              <figure class="avatar-profile">
                <span class="avatar-title bg-avatar rounded-circle">YH</span>
              </figure>

              <h6 class="font14 mt-4">Yolanda Hutajulu</h6>
              <h6 class="font12 text-muted mb-1">
                Cust ID :
                <a href="#" class="text-green">233229302320</a>
              </h6>
              <div
                class="sidebar-body"
                style="padding: 10px; overflow: hidden; outline: none;"
                tabindex="7"
              >
                <form class="text-left">
                  <div class="form-group-cwc">
                    <label for="custID" class="col-form-label">Address</label>
                    <input type="text" class="form-control no-border" id="cust_name" />
                  </div>
                  <div class="form-group-cwc">
                    <label for="custID" class="col-form-label">Company</label>
                    <input type="text" class="form-control no-border" id="category" />
                  </div>
                  <div class="form-group-cwc">
                    <label for="custID" class="col-form-label">HP</label>
                    <input type="text" class="form-control no-border" id="sub_category" />
                  </div>
                  <div class="form-group-cwc">
                    <label for="custID" class="col-form-label">HP</label>
                    <input type="text" class="form-control no-border" id="remark" />
                  </div>
                  <div class="form-group-cwc">
                    <label for="custID" class="col-form-label">Phone</label>
                    <input type="text" class="form-control no-border" id="feedback" />
                  </div>

                  <button
                    type="submit"
                    class="btn btn-md btn-green btn-block"
                    style="margin-top:1rem;"
                  >Save</button>
                </form>
              </div>
            </div>
            <div class="tab-pane m20" id="cwc" role="tabpanel">
              <form>
                <div class="form-group-cwc">
                  <label for="custID" class="col-form-label">Cust Name</label>
                  <input type="text" class="form-control no-border" id="cust_name" />
                </div>
                <div class="form-group-cwc">
                  <label for="custID" class="col-form-label">Category</label>
                  <input type="text" class="form-control no-border" id="category" />
                  <a data-toggle="modal" data-target="#categoryModal">
                    <i class="search_icon position-abs" style="width:17px !important;"></i>
                  </a>
                </div>
                <div class="form-group-cwc">
                  <label for="custID" class="col-form-label">Sub Category</label>
                  <input type="text" class="form-control no-border" id="sub_category" />
                </div>
                <div class="form-group-cwc">
                  <label for="custID" class="col-form-label">Remark</label>
                  <input type="text" class="form-control no-border" id="remark" />
                </div>
                <div class="form-group-cwc">
                  <label for="custID" class="col-form-label">Feedback</label>
                  <input type="text" class="form-control no-border" id="feedback" />
                </div>
                <ul class="list-group list-group-flush">
                  <li
                    class="list-group-item-top"
                    style="border-top: 0px;
                                            border-bottom: 1px solid rgba(0, 0, 0, .125);"
                  >
                    <div class="users-list-body text-left">
                      <h6 class="font12">Sentimen</h6>
                      <p class="text-muted font18">
                        <i
                          class="em em-slightly_frowning_face"
                          aria-role="presentation"
                          aria-label="SLIGHTLY FROWNING FACE"
                          style="width:50px"
                        ></i>
                        <i
                          class="em em-neutral_face"
                          aria-role="presentation"
                          aria-label="NEUTRAL FACE"
                          style="width:50px"
                        ></i>
                        <i
                          class="em em-slightly_smiling_face"
                          aria-role="presentation"
                          aria-label="SLIGHTLY SMILING FACE"
                          style="width:50px"
                        ></i>
                      </p>
                    </div>
                  </li>
                </ul>
                <button
                  type="submit"
                  class="btn btn-md btn-green btn-block"
                  style="margin-top:4rem;"
                >Submit</button>
              </form>
            </div>
            <div class="tab-pane" id="journey" role="tabpanel">
              <div class="card-journey">
                <div class="row mb-2">
                  <div class="col-md-6">
                    <h6 class="font10">
                      <i class="fa fa-clock-o mr-2"></i>27 Nov 2019 on
                      08:20:10
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm bg-green-positive ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Positive</button>
                  </div>
                </div>
                <div class="row mb-2">
                  <div class="col-md-6">
                    <h6 class="font9">
                      <i class="fa fa-circle text-green ml-1 mr-2 text-muted"></i>Category
                      : Complaint
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm btn-dark ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Remark &amp; Feedback</button>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <h6 class="font9">
                      <i class="fa fa-circle text-green ml-1 mr-2 text-muted"></i>Subcategory
                      : Banking
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm btn-dark ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Interaction</button>
                  </div>
                </div>
              </div>
              <div class="card-journey">
                <div class="row mb-2">
                  <div class="col-md-6">
                    <h6 class="font10">
                      <i class="fa fa-clock-o mr-2"></i>27 Nov 2019 on
                      08:20:10
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm bg-green-positive ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Positive</button>
                  </div>
                </div>
                <div class="row mb-2">
                  <div class="col-md-6">
                    <h6 class="font9">
                      <i class="fa fa-circle text-green ml-1 mr-2 text-muted"></i>Category
                      : Complaint
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm btn-dark ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Remark &amp; Feedback</button>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <h6 class="font9">
                      <i class="fa fa-circle text-green ml-1 mr-2 text-muted"></i>Subcategory
                      : Banking
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm btn-dark ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Interaction</button>
                  </div>
                </div>
              </div>
              <div class="card-journey">
                <div class="row mb-2">
                  <div class="col-md-6">
                    <h6 class="font10">
                      <i class="fa fa-clock-o mr-2"></i>27 Nov 2019 on
                      08:20:10
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm bg-green-positive ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Positive</button>
                  </div>
                </div>
                <div class="row mb-2">
                  <div class="col-md-6">
                    <h6 class="font9">
                      <i class="fa fa-circle text-green ml-1 mr-2 text-muted"></i>Category
                      : Complaint
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm btn-dark ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Remark &amp; Feedback</button>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <h6 class="font9">
                      <i class="fa fa-circle text-green ml-1 mr-2 text-muted"></i>Subcategory
                      : Banking
                    </h6>
                  </div>
                  <div class="col-md-6">
                    <button
                      type="button"
                      class="btn btn-sm btn-dark ml-4 font8"
                      style="
                                                padding: 4px;"
                    >Interaction</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </ul>
        <div
          id="ascrail2006"
          class="nicescroll-rails nicescroll-rails-vr"
          style="width: 4px; z-index: auto; cursor: default; position: absolute; top: 190px; left: 327px; height: 417px; display: none;"
        >
          <div
            class="nicescroll-cursors"
            style="position: relative; top: 0px; float: right; width: 4px; height: 0px; background-color: rgba(66, 66, 66, 0.2); border: 0px; background-clip: padding-box; border-radius: 5px;"
          ></div>
        </div>
        <div
          id="ascrail2006-hr"
          class="nicescroll-rails nicescroll-rails-hr"
          style="height: 4px; z-index: auto; top: 603px; left: 0px; position: absolute; cursor: default; display: none;"
        >
          <div
            class="nicescroll-cursors"
            style="position: absolute; top: 0px; height: 4px; width: 0px; background-color: rgba(66, 66, 66, 0.2); border: 0px; background-clip: padding-box; border-radius: 5px;"
          ></div>
        </div>
      </div>
    </div>
  </div>
</template>