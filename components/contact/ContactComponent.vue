<template>
  <div class="contactContainer bgGray">
    <p class="textCenter lac2 MB1 title" style="padding-top: 15px">Here Me</p>
    <div id="form-div">
      <form id="form1" class="form" @submit="onSubmitForm">
        <p class="name">
          <input
            id="name"
            name="name"
            type="text"
            class="validate[required,custom[onlyLetter],length[0,100]] feedback-input"
            placeholder="Name"
          />
        </p>

        <p class="email">
          <input
            id="email"
            name="email"
            type="text"
            class="validate[required,custom[email]] feedback-input"
            placeholder="Email"
          />
        </p>

        <p class="text">
          <textarea
            id="comment"
            name="text"
            class="validate[required,length[6,300]] feedback-input"
            placeholder="Comment"
          ></textarea>
        </p>
        <div class="submit">
          <input id="button-blue" type="submit" value="SEND" />
          <div class="ease"></div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    onSubmitForm(e) {
      e.preventDefault()
    }
  }
}
</script>

<style scoped>
.contactContainer {
  width: 100%;
  height: 600px;
}

.thisWidth {
  width: 400px;
}

.thisTextArea {
  width: 100%;
}

.thisDFlex {
  display: flex;
  justify-content: space-between;
}
#form-div {
  background-color: rgba(93, 93, 93, 0.4);
  padding: 35px 35px 50px;
  width: 450px;
  left: 50%;
  position: absolute;
  margin-top: 30px;
  margin-left: -260px;
  -moz-border-radius: 7px;
  -webkit-border-radius: 7px;
}

.feedback-input {
  color: #3c3c3c;
  font-family: Helvetica, Arial, sans-serif;
  font-weight: 500;
  font-size: 18px;
  border-radius: 0;
  line-height: 22px;
  background-color: #ffffff;
  padding: 13px 13px 13px 54px;
  margin-bottom: 10px;
  width: 100%;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  -ms-box-sizing: border-box;
  box-sizing: border-box;
  border: 3px solid rgba(0, 0, 0, 0);
}

.feedback-input:focus {
  background: #fff;
  box-shadow: 0;
  /*border: 3px solid #3498db;*/
  border-color: #424954;
  color: #424954;
  outline: none;
  /*padding: 13px 13px 13px 54px;*/
}

.focused {
  color: #424954;
  border: #424954 solid 3px;
}

/* Icons */
#name {
  background-image: url(http://rexkirby.com/kirbyandson/images/name.svg);
  background-size: 30px 30px;
  background-position: 11px 8px;
  background-repeat: no-repeat;
}

#email {
  background-image: url(http://rexkirby.com/kirbyandson/images/email.svg);
  background-size: 30px 30px;
  background-position: 11px 8px;
  background-repeat: no-repeat;
}

#comment {
  background-image: url(http://rexkirby.com/kirbyandson/images/comment.svg);
  background-size: 30px 30px;
  background-position: 11px 8px;
  background-repeat: no-repeat;
}

textarea {
  width: 100%;
  height: 150px;
  line-height: 150%;
  resize: vertical;
}

input:hover,
textarea:hover,
input:focus,
textarea:focus {
  background-color: white;
}

#button-blue {
  font-family: 'Montserrat', Arial, Helvetica, sans-serif;
  float: left; /* 플롯 중요(::after 가상요소 이용)*/
  width: 100%;
  border: #fbfbfb solid 4px;
  cursor: pointer;
  background-color: #424954;
  color: white;
  font-size: 24px;
  padding-top: 22px;
  padding-bottom: 22px;
  -webkit-transition: all 0.3s;
  -moz-transition: all 0.3s;
  transition: all 0.3s;
  margin-top: -4px;
  font-weight: 700;
}

#button-blue:hover {
  background-color: rgba(0, 0, 0, 0);
  color: #424954;
}

.ease {
  width: 0;
  height: 74px;
  background-color: #fbfbfb;
  -webkit-transition: 0.3s ease;
  -moz-transition: 0.3s ease;
  -o-transition: 0.3s ease;
  -ms-transition: 0.3s ease;
  transition: 0.3s ease;
}

.submit:hover .ease {
  width: 100%;
  background-color: white;
}
</style>
