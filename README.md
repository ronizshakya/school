# School
## Front End Design

## Registration From

## Slider(carousel)

## Modal

*Modal practice*

**June 14,2017**



![Picture](https://images.pexels.com/photos/2946/dawn-nature-sunset-trees.jpg)

one|three|two|
-|-|-
4|5|6|


```html
<div class="modal fade" id="myModal">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <button class="close" data-dismiss="modal">&times;</button>

          <h4 class="modal-title">Restration Form</h4>
        </div><!-- end modal-header -->
        <div class="modal-body">
          <h4>enter ur name</h4>

          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>

          <h4>Popovers in a modal</h4>
          <a href="#" class="btn btn-danger pop" data-toggle="popover" data-placement="top" data-original-title="You clicked it!" data-content="I knew you would.">Don't click this button</a>

          <h4>Tooltips in a modal</h4>
          <a href="" data-original-title="Tooltip" rel="tooltip">This link</a> should have a tooltip, and so should <a href="#" data-original-title="Woohoo!" rel="tooltip">this one</a>!

          <hr>

          <p><small class="text-muted">PS. This form doesn't do anything. Just a heads up.</small></p>

          <form class="form-horizontal">
            <div class="form-group">
              <label class="col-lg-2 control-label" for="inputName">Name</label>
              <div class="col-lg-10">
                <input class="form-control" id="inputName" placeholder="Name" type="text">
              </div>
            </div>

            <div class="form-group">
              <label class="col-lg-2 control-label" for="inputEmail">Email</label>
              <div class="col-lg-10">
                <input class="form-control" id="inputEmail" placeholder="Email" type="email">
              </div>
            </div>

            <div class="form-group">
              <label class="col-lg-2 control-label" for="inputMessage">Message</label>
              <div class="col-lg-10">
                <textarea class="form-control" id="inputMessage" placeholder="Message" rows="3"></textarea>
                <button class="btn btn-success pull-right" type="submit">Send!</button>
              </div>
            </div>
          </form>
        </div><!-- end modal-body -->

        <div class="modal-footer">
          <button class="btn btn-default" data-dismiss="modal" type="button">Close</button> <button class="btn btn-primary" type="button">Save changes</button>
        </div><!-- end modal-footer -->
      </div><!-- end modal-content -->
    </div><!-- end modal-dialog -->
  </div><!-- end myModal -->
  ```

