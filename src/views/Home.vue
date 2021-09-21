<template>
  <div
    class="
      bg-white
      mt-20
      pb-6
      w-3/4
      justify-center
      items-center
      overflow-hidden
      md:max-w-sm
      rounded-lg
      shadow-sm
      mx-auto
    "
  >
    <div class="relative h-40">
      <img
        class="absolute h-full w-full object-cover"
        src="https://scontent.fpbh1-1.fna.fbcdn.net/v/t1.6435-9/242176067_4899316173464739_1174720861220058223_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=e3f864&_nc_ohc=GI41mkcm6JgAX8u-dE0&_nc_ht=scontent.fpbh1-1.fna&oh=2dfb4b835a3d5111bf6358c224182c24&oe=616FB427"
      />
    </div>
    <div
      class="
        relative
        shadow
        mx-auto
        h-24
        w-24
        -my-12
        border-white
        rounded-full
        overflow-hidden
        border-4
      "
    >
      <img
        class="object-cover w-full h-full"
        src="https://scontent.fpbh1-1.fna.fbcdn.net/v/t1.6435-9/242147682_4899394690123554_3185476395714513696_n.jpg?_nc_cat=100&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=3pVj-PLfxnMAX-gGNL1&tn=wghH5QaUsrUCanE9&_nc_ht=scontent.fpbh1-1.fna&oh=78b08968f1cab81816e018c0bafdf4ea&oe=61718A7A"
      />
    </div>
    <div class="mt-16">
      <h1 class="text-lg text-center font-semibold">Tenzine Uzumakii</h1>
      <p class="text-sm text-gray-600 text-center">
        Urban Planner/ Full Stack Developer
      </p>
    </div>

    <p class="text-sm mt-5 text-center text-gray-600">Languages</p>
    <div class="pt-3 flex flex-wrap mx-6 justify-center border-t">
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-sky-600
          border-sky-600
          hover:bg-sky-600
          hover:text-sky-100
          cursor-default
        "
        v-for="language in languages"
        :key="language"
      >
        {{ language }}
      </div>
    </div>

    <p class="text-sm mt-5 text-center text-gray-600">Frameworks</p>
    <div class="pt-3 flex flex-wrap justify-center mx-6 border-t">
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-sky-900
          border-sky-900
          hover:bg-sky-900
          hover:text-sky-100
          cursor-default
        "
        v-for="framework in frameworks"
        :key="framework"
      >
        {{ framework }}
      </div>
    </div>

    <p class="text-sm mt-5 text-center text-gray-600">Skills</p>
    <div class="pt-3 flex flex-wrap justify-center mx-6 border-t">
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-gray-800
          border-gray-800
          hover:bg-gray-800
          hover:text-gray-100
          cursor-default
        "
        v-for="skill in skills"
        :key="skill"
      >
        {{ skill }}
      </div>
    </div>

    <div class="relative   rounded-b-lg mt-4 text-gray-800 text-sm font-thin bg-sky-700 p-6 bg-opacity-20">
      <div class="flex flex-col gap-2 ">
        <div class="flex gap-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="20"
            height="20"
            viewBox="0 0 24 24"
          >
            <path
              d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm3.445 17.827c-3.684 1.684-9.401-9.43-5.8-11.308l1.053-.519 1.746 3.409-1.042.513c-1.095.587 1.185 5.04 2.305 4.497l1.032-.505 1.76 3.397-1.054.516z"
            /></svg
          >17263764
        </div>
        <div class="flex gap-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="20"
            height="20"
            viewBox="0 0 24 24"
          >
            <path
              d="M12 .02c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.99 6.98l-6.99 5.666-6.991-5.666h13.981zm.01 10h-14v-8.505l7 5.673 7-5.672v8.504z"
            />
          </svg>
          nimaytenzin@gmail.com
        </div>

        <div class="flex gap-3">
          <a href="https://github.com/nimaytenzin">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
            >
              <path
                d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
              />
            </svg>
          </a>

          <a href="https://www.facebook.com/nimayztenzin/">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
            >
              <path
                d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm3 8h-1.35c-.538 0-.65.221-.65.778v1.222h2l-.209 2h-1.791v7h-3v-7h-2v-2h2v-2.308c0-1.769.931-2.692 3.029-2.692h1.971v3z"
              />
            </svg>
          </a>

          <a href="https://www.instagram.com/nimaytenzin/">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
            >
              <path
                d="M14.829 6.302c-.738-.034-.96-.04-2.829-.04s-2.09.007-2.828.04c-1.899.087-2.783.986-2.87 2.87-.033.738-.041.959-.041 2.828s.008 2.09.041 2.829c.087 1.879.967 2.783 2.87 2.87.737.033.959.041 2.828.041 1.87 0 2.091-.007 2.829-.041 1.899-.086 2.782-.988 2.87-2.87.033-.738.04-.96.04-2.829s-.007-2.09-.04-2.828c-.088-1.883-.973-2.783-2.87-2.87zm-2.829 9.293c-1.985 0-3.595-1.609-3.595-3.595 0-1.985 1.61-3.594 3.595-3.594s3.595 1.609 3.595 3.594c0 1.985-1.61 3.595-3.595 3.595zm3.737-6.491c-.464 0-.84-.376-.84-.84 0-.464.376-.84.84-.84.464 0 .84.376.84.84 0 .463-.376.84-.84.84zm-1.404 2.896c0 1.289-1.045 2.333-2.333 2.333s-2.333-1.044-2.333-2.333c0-1.289 1.045-2.333 2.333-2.333s2.333 1.044 2.333 2.333zm-2.333-12c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.958 14.886c-.115 2.545-1.532 3.955-4.071 4.072-.747.034-.986.042-2.887.042s-2.139-.008-2.886-.042c-2.544-.117-3.955-1.529-4.072-4.072-.034-.746-.042-.985-.042-2.886 0-1.901.008-2.139.042-2.886.117-2.544 1.529-3.955 4.072-4.071.747-.035.985-.043 2.886-.043s2.14.008 2.887.043c2.545.117 3.957 1.532 4.071 4.071.034.747.042.985.042 2.886 0 1.901-.008 2.14-.042 2.886z"
              />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      languages: ["Javascript", "GoLang", 'Dart',"HTML/CSS3", "PHP", "Python", "SQL"],
      frameworks: [
        "Vue JS",
        "Angular",
        "Tailwind CSS",
        "Laravel",
        "Node JS",
        "Next JS",
        "POSTGRESql",
        "MYSQL",
        'Flutter'
      ],
      skills: [
        "Database Design",
        "Systems Design",
        "Shared Hosting",
        "Geospatial Analysis",
        "Graphics Design",
      ],
    };
  },
};
</script>
