
<template>
    <form class="w-[260px] h-[260px] relative" action="">
         <table class="absolute top-[30px] left-[30px] bottom-[30px] w-[200px] h-[200px]">
            <tr><td class="text-xs">회사 공고 등록 후 AI 코칭 받기</td></tr>
            <tr>
                <th><label class="text-[9.5px] font-medium" for="" >회사이름</label></th>
                <td>
                    <input class="text-[9.5px]" type="text" list="list" placeholder="회사이름을 작성해주세요">
                    <datalist id="list">
                        <option value="회사1"></option>
                        <option value="회사2"></option>
                        <option value="회사3"></option>
                    </datalist>
                </td>
            </tr>
            <tr>
                <th><label class="text-[9.5px] font-medium" for="">지원 직무</label></th>
                <td>
                    <select class="text-[9.5px]" name="" id="" placeholder="gg">
                        <option value="" disabled selected hidden>원하는 직무를 선택해주세요</option>
                        <option>프론트엔드</option>
                        <option>백엔드</option>
                    </select>
                </td>
            </tr>
            <tr>
                <th><label class="text-[9.5px] font-medium" for="">경력</label></th>
                <td>
                    <select class="text-[9.5px]" name="" id="">
                        <option value="" disabled selected hidden>신입/경력</option>
                        <option>신입</option>
                        <option>경력</option>
                    </select>
                </td>
            </tr>
            <tr>
                <th><label class="text-[9.5px] font-medium" for="date">지원날짜</label></th>
                <td><input class="text-[9.5px]"  type="date"></td>
            </tr>
              <tr>
                  <td>
                      <button>예시 보기</button>
                  </td>
                  <td>
                      <button>자소서 검사받기</button>
                  </td>
              </tr>
        </table>
    </form>
  </template>
  
  
  