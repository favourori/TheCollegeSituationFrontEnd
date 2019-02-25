<template>
  <div>
    <div>
      <form>
        <div class="card z-depth-0" style="width: 770px; padding: 50px 10px; margin: 80px auto">
          <div class="row">
            <p class style="font-size: 23px; padding: 0 10px; font-weight: 400">Upload School
              <br>
              <small
                style="font-size: 14px; color: red; background: #ecf0f1; padding: 6px 16px"
              >Be sure to double check all info before submitting. If you submit any Wrong info, you won't get paid 🙃</small>
            </p>
            <br>

            <div class="input-field col s12">
              <input id="name" type="text" required class="validate">
              <label for="name">Name of school</label>
            </div>
          </div>



        

          <div class="row">
            <div class="input-field col s12">
              <input id="desc" type="text" required class="validate">
              <label for="desc">Brief Description</label>
            </div>
          </div>
          <!--population-->
          <div class="row">
            <div class="input-field col s12">
              <input id="undergradPop" type="text" required class="validate">
              <label for="undergradPop">Undergraduate Population</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="intTuition" type="text" required class="validate">
              <label for="intTuition">Tuition International</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="localTuition" type="text" required class="validate">
              <label for="localTuition">Tuition Local</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="website" type="text" required class="validate">
              <label for="website">School Website</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="address" type="text" required class="validate">
              <label for="address">School Address</label>
            </div>
          </div>


          <div class="row">
            <div class="input-field col s12">
              <input id="city" type="text" required class="validate">
              <label for="city">City</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="state" type="text" required class="validate">
              <label for="state">State</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="zip" type="text" required class="validate">
              <label for="zip">Zip Code</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="gradRate" type="text" required class="validate">
              <label for="gradRate">Graduation Rate</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="acceptanceRate" type="text" required class="validate">
              <label for="acceptanceRate">Acceptance Rate</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="genPhone" type="text" required class="validate">
              <label for="genPhone">General Phone Number</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="intPhone" type="text" required class="validate">
              <label for="intPhone">International Office Phone Number</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="schoolPhoto" type="text" required class="validate">
              <label for="schoolPhoto">Upload Photo here</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="courses" type="text" required class="validate">
              <label for="courses">Link to Degress & Major</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="scholarships" type="text" required class="validate">
              <label for="scholarships">Link to Scholarships</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              

  <select class="browser-default" required>
    <option value="" > — Select school Category — </option>
    <option value="1">Public</option>
    <option value="2">Private</option>
  
  </select>
            



            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="avgSAT" type="text" required class="validate">
              <label for="avgSAT">Average SAT</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="avgACT" type="text" required class="validate">
              <label for="avgACT">Average ACT</label>
            </div>
          </div>

          <div class="row">
              <select class="browser-default" required>
    <option value="" > — Select school type — </option>
    <option value="1">University (4 year)</option>
    <option value="2">Community College (2 years)</option>
  
  </select>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="aboutLocation" type="text" required class="validate">
              <label for="aboutLocation">About school location (Link to Wikipedia)</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="admissions" type="text" required class="validate">
              <label for="admissions">Admissions (Link to admission)</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="academics" type="text" required class="validate">
              <label for="academics">Academics (Link to Academics)</label>
            </div>
          </div>

          <div class="row">
            <div class="input-field col s12">
              <input id="fastFacts" required type="text" class="validate">
              <label for="fastFacts">Fast fact (Brief summary of facts from school website)</label>
              <br>
              <br>
              <br><br/>
              <button
                class="btn waves-effect waves-light z-depth-0"
                style="width: 100%"
                type="submit"
                name="action"
              >Upload school</button>



  
              <br>
              <br>
            </div>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "addschool",
  data() {
    return {};
  }
};
</script>

<style>
</style>
