<template>
  <div class="p-sub-CS1_3_1_1T">
    <div class="submain-section">
      <div class="toparea-contents">
        <div class="toparea-contents-bg">
          <div class="sub-page-position-wrap">
            <div class="sub-page-position">
              <ul class="sub-position-list">
                <li><a href="#">개인</a></li>
                <li><a href="#">고객지원</a></li>
                <li>
                  <a href="#" class="arrow-expand">온라인문의</a>
                  <ul class="position-depth-2">
                    <li><a href="">온라인서브메뉴1</a></li>
                    <li><a href="">온라인서브메뉴2</a></li>
                    <li><a href="">온라인서브메뉴3</a></li>
                    <li><a href="">온라인서브메뉴4</a></li>
                    <li><a href="">온라인서브메뉴5</a></li>
                    <li><a href="">온라인서브메뉴6</a></li>
                    <li><a href="">온라인서브메뉴7</a></li>
                    <li><a href="">온라인서브메뉴8</a></li>
                  </ul>
                </li>
                <li>
                  <a href="#" class="arrow-expand">설치가능 지역조회</a>
                  <ul class="position-depth-2 is-hide">
                    <li><a href="#">가까운 매장 찾아보기</a></li>
                    <li><a href="#">자주하는 질문</a></li>
                    <li><a href="#">1:1 문의</a></li>
                    <li><a href="#">칭찬합니다</a></li>
                    <li><a href="#">이용자 피해 예방 가이드</a></li>
                    <li><a href="#">통화품질 개선요청</a></li>
                  </ul>
                </li>
              </ul>
            </div>
          </div>
          <div class="sub-top">
            <div class="sub-top-box">
              <h1 class="h1">설치신청 변경</h1>
              <div class="brief-info-type-1">
                <p class="brief-info-item">
                  <strong class="item-title">가입정보</strong>
                  <span class="item-info">결합</span>
                  <span class="item-info">500-45-**-69**</span>
                  <span class="item-info">가족무한사랑 (유무선)</span>
                </p>
              </div>
              <button class="c-btn-outline c-sm">가입 서비스 더보기</button>
            </div>
          </div>
        </div>
      </div>
      <!-- //.toparea-wrap -->
      <div class="middlearea-contents -cont-mt-0">
        <div class="middlearea">
          <!-- 탭 메뉴 영역 -->
          <div class="c-tabmenu-wrap">
            <div class="c-tabmenu-tab c-tab-default">
              <ul>
                <li class="is-active">
                  <a href="#">댁외 설치장소 변경 신청 <span class="is-blind">선택됨</span></a>
                </li>
                <li>
                  <a href="#">댁내 설치장소 변경 신청</a>
                </li>
                <li>
                  <a href="#">신청내역 조회 및 변경</a>
                </li>
              </ul>
            </div>
          </div>
          <!-- //탭 메뉴 영역 -->

          <!-- 탭 컨텐츠 영역 -->
          <div class="c-tabcontent-box">
            <div class="c-page-section">
              <h2 class="is-blind">댁외 설치장소 변경 신청</h2>

              <div class="row c-table">
                <b-table-simple bordered class="c-table-row">
                  <caption>
                    선택한 가입정보 : 가입서비스, 현재 설치장소에 대한 표
                  </caption>
                  <colgroup>
                    <col style="width: 240px" />
                    <col style="width: 480px" />
                    <col style="width: 240px" />
                    <col style="width: auto" />
                  </colgroup>
                  <b-tbody>
                    <b-tr>
                      <b-th>가입서비스</b-th>
                      <b-td>모바일/인터넷/IPTV/인터넷전화/스마트홈</b-td>
                      <b-th>현재 설치장소</b-th>
                      <b-td>서울시 동작구 상도로 15길 *** ******(***)</b-td>
                    </b-tr>
                  </b-tbody>
                </b-table-simple>
              </div>
              <ul class="c-bullet-type-cirlce">
                <li>이사 등의 이유로 인터넷, IPTV등 서비스의 설치장소를 변경 신청 할 수 있습니다.</li>
              </ul>
            </div>

            <!-- //이하 컨텐츠 생략 -->
          </div>

          <div class="c-tabcontent-box is-hide">
            <div class="c-page-section">
              <h2 class="is-blind">댁내 설치장소 변경 신청</h2>
              해당페이지탭내용참조-2
            </div>
          </div>
          <div class="c-tabcontent-box is-hide">
            <div class="c-page-section">
              <h2 class="is-blind">신청내역 조회 및 변경</h2>
              해당페이지탭내용참조-3
            </div>
          </div>
          <!-- //탭 컨텐츠 영역 -->
        </div>
        <!-- //.middlearea -->
      </div>
      <!-- //.middlearea-contents -->
    </div>
    <!-- //.submain-section  -->

    <div>
      <!-- Popup-->
      <b-modal ref="my-modal" dialog-class="m-bv-modal c-layer-popup-800">
        <!-- 헤더 -->
        <template #modal-header="{ close }">
          <h1 class="h3">댁외 설치장소 변경 예약정보 확인</h1>
          <button class="c-btn-close" type="button" @click="close()">레이어 닫기</button>
        </template>
        <!-- // 헤더 -->
        <!-- 바디 -->
        <template #default="{}">
          <div class="c-body-content">
            <section class="c-section -ta-c">
              <p class="h4">설치장소 변경 신청을 완료하지 못했습니다. 이전설치 전문상담사의 <br />상담이 필요합니다. 연락처를 남겨주시면 전화 드리겠습니다.</p>
            </section>

            <section class="c-section">
              <h2 class="h5">이전설치 전문상담 신청</h2>
              <div class="row c-table">
                <b-table-simple bordered class="c-table-row">
                  <caption>
                    이전설치 전문상담 신청 정보 : 변경 설치 장소 정보 및 댁내 대기자 이름, 연락 가능한 전화번호 입력에 대한 표
                  </caption>
                  <colgroup>
                    <col style="width: 216px" />
                    <col style="width: auto" />
                  </colgroup>
                  <b-tbody>
                    <b-tr>
                      <b-th>변경 설치 장소</b-th>
                      <b-td>경기도 성남시 400-11</b-td>
                    </b-tr>
                    <b-tr>
                      <b-th>
                        <label class="c-label" for="cfrmInp-1-1">
                          댁내 대기자 이름
                          <span class="is-need"><i class="is-blind">필수항목</i></span>
                        </label>
                      </b-th>
                      <b-td>
                        <div class="c-inpform">
                          <input id="cfrmInp-1-1" type="text" name="" title="이름을 입력해 주세요." class="c-inp" />
                        </div>
                      </b-td>
                    </b-tr>
                    <b-tr>
                      <b-th>
                        <label class="c-label" for="cfrmSelect-1-1">
                          연락 가능한 전화번호
                          <span class="is-need"><i class="is-blind">필수항목</i></span>
                        </label>
                      </b-th>
                      <b-td>
                        <div class="c-inpform-group column-telnumber">
                          <div class="c-selform">
                            <span class="is-blind">통신사 번호</span>
                            <select id="cfrmSelect-1-1" name="" class="c-select" title="연락처 통신사 번호 선택">
                              <option value="" selected>010</option>
                              <option>070</option>
                            </select>
                          </div>
                          <div class="c-inpform">
                            <span class="is-blind">연락처 번호</span>
                            <input id="cfrmInp-1-2" type="text" name="" placeholder="" title="연락처 나머지 8자리 입력" class="c-inp" />
                            <button class="c-btn-clear" title="입력한 문자 삭제"><span class="is-blind">삭제</span></button>
                          </div>
                        </div>
                      </b-td>
                    </b-tr>
                  </b-tbody>
                </b-table-simple>
              </div>
              <ul class="c-bullet-type-cirlce">
                <li>이전 설치상담 직통전화 : 1644-2424 <i class="c-vline-type-1" aria-hidden="true"></i> 기타 상담전화 :국번없이 101</li>
              </ul>
            </section>
          </div>
        </template>
        <!-- // 바디 -->
        <!-- 푸터 -->
        <template #modal-footer="{ ok, cancel }">
          <div class="c-btn-group">
            <button class="c-btn-cancel c-sm" @click="ok()">취소</button>
            <button class="c-btn-ok c-sm" @click="cancel()">확인</button>
          </div>
        </template>
        <!-- // 푸터 -->
      </b-modal>
      <!-- //Popup-->
    </div>
  </div>
</template>

<script>
export default {
  layout: 'l-sub-main',
  data() {
    return {};
  },
  head() {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: '/style/css/p-main-sub-customer.min.css',
        },
      ],
    };
  },
  mounted() {
    this.$refs['my-modal'].show();
  },
};
</script>

<style lang="scss"></style>
