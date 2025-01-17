# Detecting Fallen

본 리포지토리는 제안된 시스템의 테스트 영상을 제공한다. 각각의 영상은 가상 환경과 실제 필드 환경에서의 테스트 결과를 보여준다.

---

### 1. 가상 환경 테스트
![가상 환경 테스트](https://github.com/kdykmg/Detecting_Fallen/blob/main/gazebo.gif)

가제보(Gazebo) 시뮬레이터에서 수행된 테스트로, 드론이 가상 환경에서 쓰러진 사람을 탐지하는 과정을 보여준다.



### 2. 필드 테스트 (비교: 스택 알고리즘 미 적용 vs 적용)

<table style="width: 100%; text-align: center; border-collapse: collapse;">
  <tr>
    <td align="center" width="50%" style="border: 2px solid #ccc; padding: 10px; vertical-align: top;">
      <table style="width: 100%; border-collapse: collapse; border: none; text-align: center;">
        <tr>
          <td style="border-bottom: 2px solid #ccc; padding: 10px;">
            <strong>스택 알고리즘 미 적용</strong>
          </td>
        </tr>
        <tr>
          <td style="padding: 10px;">
            <img src="https://github.com/kdykmg/Detecting_Fallen/blob/main/Non%20Stack.gif" alt="필드 테스트 - 논 스택" style="width: 100%; max-width: 300px;">
          </td>
        </tr>
        <tr>
          <td style="border-top: 2px solid #ccc; padding: 10px;">
            필드 환경에서 신뢰 스택 알고리즘을 사용하지 않은<br> 상태에서 드론이 탐지 작업을 수행한 결과를 보여줍니다.
          </td>
        </tr>
      </table>
    </td>
    <td align="center" width="50%" style="border: 2px solid #ccc; padding: 10px; vertical-align: top;">
      <table style="width: 100%; border-collapse: collapse; border: none; text-align: center;">
        <tr>
          <td style="border-bottom: 2px solid #ccc; padding: 10px;">
            <strong>스택 알고리즘 적용</strong>
          </td>
        </tr>
        <tr>
          <td style="padding: 10px;">
            <img src="https://github.com/kdykmg/Detecting_Fallen/blob/main/Stack.gif" alt="필드 테스트 - 스택" style="width: 100%; max-width: 300px;">
          </td>
        </tr>
        <tr>
          <td style="border-top: 2px solid #ccc; padding: 10px;">
            필드 환경에서 신뢰 스택 알고리즘을 적용하여 드론이<br> 탐지 작업을 수행한 결과를 보여줍니다.
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>
