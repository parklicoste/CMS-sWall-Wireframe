<template>
        <div class="col col-lg-8">
            <h5 class="row mt-3 mb-3">Bird Animation</h5>
                <form>
                    <div class="form-group row">
                        <label for="file-name" class="col-sm-4 col-form-label">Current File*</label>
                        <div class="col-sm-6">
                        <input type="text"  class="form-control" id="file-name" placeholder="sample.gif">
                        </div>
                    </div>
                </form>

                <div class="input-group mb-3">
                    <div class="input-group-prepend">
                        <span class="input-group-text">New File</span>
                    </div>
                    <div class="custom-file">
                        <input type="file" class="custom-file-input" id="inputGroupFile01">
                        <label class="custom-file-label" for="inputGroupFile01">Choose file</label>
                    </div>
                </div>
                <button type="button" class="btn btn-primary btn-lg mt-3" style="margin-left: 30%;">Submit</button>
        </div>
        
</template>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  padding-left: 50px;
  vertical-align: middle;
}

</style>

<script>
export default {
    data: () => {
        return {
        uploadLinks: [
              { text: 'Game',
                path: '/upload/game'
            },
            { text: 'Media',
              path: '/upload/media'
              },
            { text: 'Browser',
              path: '/upload/browser'
              },
            { text: 'Idle Media',
              path: '/upload/idleMedia'
              },
            { text: 'Bird Animation',
              path: '/upload/birdAnimation'
              },
            { text: 'Background Image',
              path: '/upload/backgroundImage'
              }
            ]
        }
    }
}
</script>